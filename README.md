
<p align="center"><img src="https://github.com/user-attachments/assets/39c1481a-124f-45b5-bff6-b71b0777faf1" width="500"/></p>

<h2 align="center"><strong> Pipeline de Infraestrutura (AWS + Terraform + Github Actions + Multi Env) </strong></h2>

<h4 align="center">
  Para um maior entendimento do código, assista ao vídeo no Youtube, <a href="https://www.youtube.com/watch?v=1TNAUW7_bC0">Clique aqui</a>. 

<h4 align="center">
  Atividade realizada com base na Master Class do 
  <a href="https://github.com/buildrun-tech">@Brunograna</a>.
</h4>

### Fluxo da Pipeline

![Image](https://github.com/user-attachments/assets/618feb78-93db-4591-9a5d-5d39000b67c2)

![Image](https://github.com/user-attachments/assets/23b9915b-ade0-49aa-a15d-b3662977130e)

### Como começar?

 * Crie o Identity Provider do Github em sua conta AWS
 * Crie uma IAM Role em sua conta AWS (Permissão mínimia de S3 e DynamoDB)
 * Crie um Bucket S3 em sua conta AWS (Habilite o Bucket Versioning)
 * Crie uma tabela no DynamoDB na sua conta AWS (PartitionKey com o nome "LockID")
 * Clone esse repositório
 * Configure os arquivos workflow
 * Pronto! Você já está habilitado para implantar infras na AWS com Terraform via pipeline

### Referências

https://aws.amazon.com/blogs/security/use-iam-roles-to-connect-github-actions-to-actions-in-aws/
