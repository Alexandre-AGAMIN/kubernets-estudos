# kubernets-estudos
Repo dedicad oa estudos de kubernets


Kubectl get nodes
 - usado para pegar os nós
kubectl run nginx-pod --image=nginx:latest
 - usado para criar uma pode com determinada imagem
kubectl get pods
 - usado para pegar as pods
 * kubectl get pod -o wide
  - usado para pegar a pod com ingormações mais detalhadas
kubectl describe pod nginx-pod
 - usa opara detalhar as pods
kubectl apply -f .\primeiro-pod.yaml
 - usado aprar criar uma pod com determinado arquivo declarativo de extensão yaml
kubectl delete pod nginx-pod
 - usado para deletar determinado pod
 kubectl delete pod -f .\primeiro-pod.yaml
 - usado para deletar o pod usando o arquivo de definição (-f de file)