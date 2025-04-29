# Azure Devops

### Configurar terraform files
1. site.tf  
  1.1. <rg_name>
2. terraform.tfstate  
  2.1. <rg_name>  
  2.2. <sub_key>  
  2.3. <private_key>  

### Utilização de pipelines

1. Criação do Resource group   
  1.1. resource-group.png
  1.2. resource-group-tags.png
2. Criação do infra  
  2.1. create_infra.png
3. App Register  
  3.1. sp_app_register.png
  3.1. sp_certificate_key.png
4. Criação do repos no Azure Devops  
  4.1. create_repos.png
5. Rodar a pipeline  
  5.1. run_pipeline.png  

  
Até o momento não rodou o init do terraform