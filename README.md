# aks-test

```
kb create -f .\my-first-pod.yaml
kb get pod
kb describe pod my-pod
kb port-forward my-pod 8000:3000
kb expose pod my-pod --type=NodePort --name=my-pod-service
kb get service
kb attach my-pod -i
kb exec my-pod -- ls /app
kb get pod --show-lables
kb label pods my-pod version=latest
kb run -i --tty alpine --image=alpine --restart=Never -- sh
/ # apk add --no-cache curl
/ # curl http://10.244.1.12:3000
/ # cat /etc/resolv.conf
```

## Reference
[Kubernetes 30天學習筆記系列 第 5 篇] https://ithelp.ithome.com.tw/articles/10193232