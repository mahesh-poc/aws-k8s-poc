# aws-test


docker build -t fsl-challenge-app:latest .
kubectl port-forward -n production service/fsl-service 8080:8080



####



  323  git remote add origin https://github.com/mahesh-poc/test.git
  324  git remote set-url origin https://github.com/mahesh-poc/test.git
  325  git remote -v
  326  git switch -c main
  327  git push -u origin main
  328  git push -u origin HEAD:main
  329  git pull --rebase
  330  git push -u origin HEAD:main
  331  git push -u origin HEAD:main --force
