# Sameple Practice for Deploying Windows Server 2022
# Deploying IIS Server for company website
- Step 1 : Create providers.tf
    >required_providers
- Step 2 : Create main.tf
    >resource_block
    >create_vnet
    >create_subnet
    >create_publicip
    >create_nsg_rules | Inbound & Outbound
    >create_nic & ip_configuration
    >connect sg to nic
    >storage_account_for_boot_diagonsitics
    >create vm - os_disk,os_image,boot_diagonsitics
    >install IIS
    >generate_password
- Step 3 : variables.tf
- Step 4 : output.tf to display some information
    >display password,ip,resourcegroup_name
- Step 5 : Apply Terrform to Azure Resources
    >terraform init
    >terraform apply -auto-approve