# ProjetoPsi

Tudo a correr usando o appserver através do ssh.

Frontend:
ng serve --port 3027 --host 0.0.0.0 --disableHostCheck true

Backend:
mongodb://psi027:psi027@localhost:27017/psi027?retryWrites=true&authSource=psi027

Para aceder à DB:
mongo -username psi027 --password --authenticationDatabase psi027 appserver.alunos.di.fc.ul.pt/psi027