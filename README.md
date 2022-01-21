<!-- @format -->

# How to run this k8s deployement

1. `git clone https://github.com/hamzazahidulislam/k8s-mongo-exprees`
2. go to project folder.
3. Run k8s deployement `kubectl apply -f .`

### please make sure before you apply this command `kubectl apply -f .` you have must install [Nginx Igress Controller](https://kubernetes.github.io/ingress-nginx/deploy/)

Expected Output:

```
ingress.networking.k8s.io/example-ingress created
configmap/mongodb-configmap created
deployment.apps/mongo-express created
service/mongo-express-service created
secret/mongodb-secret created
deployment.apps/mongodb-deployment created
service/mongodb-service created
```

4. Open `http://localhost` or [SYSTEM_IP_ADDRESS](https://superuser.com/questions/433988/how-to-find-the-ip-address-of-a-vm-running-on-vmware-or-other-methods-of-using/531635) in your browser.
After open Browser, you will see the following Result.
<center>
<a href="result.png"><img src="result.gif" alt="result" border="0"></a><br />
</center>
