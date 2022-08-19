# recopilación_material-Microsoft-AZ-500-
![az-500](https://user-images.githubusercontent.com/40150899/185011826-3e4156d1-77fa-481d-bd74-2ee67e3de559.png)

Recopilación personal sobre la documentación oficial publicada por Microsoft para poder prepararse para la certificación AZ-500: Microsoft Azure Security Technologies.

Se van a ir ordenando los diversos temas que considero importantes estudiar y practicar en base al temario oficial que propone Microsoft para la AZ-500.
<hr>
<hr>

### Administrar identidades y accesos (30-35 %)
<hr>

#### Configurar Microsoft Azure Active Directory para cargas de trabajo

- [Crear registro de aplicación](https://docs.microsoft.com/es-es/azure/active-directory/develop/howto-create-service-principal-portal)
- [Configurar los alcances de los permisos de registro de la aplicación](https://docs.microsoft.com/es-es/azure/active-directory/develop/v2-permissions-and-consent)
- [Administrar consentimiento de permiso de registro de aplicaciones](https://docs.microsoft.com/es-mx/azure/active-directory/develop/v2-permissions-and-consent)
- [Configurar la autenticación multifactor](https://docs.microsoft.com/es-mx/azure/active-directory/authentication/howto-mfa-mfasettings)
- [Administrar grupos de directorios de Microsoft Azure AD](https://docs.microsoft.com/es-mx/azure/active-directory/fundamentals/active-directory-groups-members-azure-portal)
- [Administrar usuarios de Microsoft Azure AD](https://docs.microsoft.com/es-mx/azure/active-directory/fundamentals/add-users-azure-active-directory)
- [Instalar y configurar la conexión de Microsoft Azure AD Connect](https://docs.microsoft.com/es-es/azure/active-directory/hybrid/how-to-connect-install-roadmap)
- [Implementar políticas de acceso condicional](https://docs.microsoft.com/es-mx/azure/active-directory/conditional-access/plan-conditional-access)
- [Configurar Microsoft AD Identity Protection](https://docs.microsoft.com/es-es/azure/active-directory/identity-protection/overview-identity-protection)

<hr>

#### Configurar la administración de identidades con privilegios de Microsoft Azure AD

- [Supervisar el acceso privilegiado](https://docs.microsoft.com/es-mx/azure/active-directory/privileged-identity-management/pim-how-to-use-audit-log)
- [Configurar revisiones de acceso](https://docs.microsoft.com/es-mx/azure/active-directory/governance/access-reviews-overview)
- [Activar Privileged Identity Management (PIM)](https://docs.microsoft.com/es-mx/azure/active-directory/privileged-identity-management/pim-deployment-plan)

<hr>

#### Configurar la seguridad del inquilino de Microsoft

- [Transferir suscripciones de Azure entre inquilinos de Microsoft Azure AD](https://docs.microsoft.com/es-mx/azure/active-directory/fundamentals/active-directory-how-subscriptions-associated-directory)
- [Administre el acceso de la API a las suscripciones y los recursos de Microsoft Azure](https://docs.microsoft.com/es-mx/azure/role-based-access-control/role-assignments-portal?tabs=current)

<hr>
<hr>

### Implementación de la protección de la plataforma (15-20 %)
<hr>

#### Implementar la seguridad de la red

- [Configurar la conectividad de la red virtual](https://docs.microsoft.com/es-mx/azure/virtual-network/virtual-networks-overview)
- [Configurar grupos de seguridad de red (NSG)](https://docs.microsoft.com/es-mx/azure/virtual-network/manage-network-security-group)
- [Crear y configurar Microsoft Azure Firewall](https://docs.microsoft.com/es-mx/azure/firewall/tutorial-firewall-deploy-portal)
- [Crear y configurar grupos de seguridad de aplicaciones (ASG)](https://docs.microsoft.com/es-mx/azure/virtual-network/tutorial-filter-network-traffic#associate-network-interfaces-to-an-asg)
- [Configurar la gestión de acceso remoto](https://docs.microsoft.com/es-mx/azure/security/fundamentals/management)

<hr>

#### Implementar la seguridad del host

- [Configurar la seguridad de punto final dentro de la VM](https://docs.microsoft.com/es-mx/azure/defender-for-cloud/supported-machines-endpoint-solutions-clouds-containers?tabs=azure-aks#supported-endpoint-protection-solutions-)
- [Configurar la seguridad de la VM](https://docs.microsoft.com/es-mx/azure/security/fundamentals/iaas)
- [Configurar actualizaciones del sistema para VM en Microsoft Azure](https://docs.microsoft.com/es-mx/azure/security/fundamentals/iaas#manage-your-vm-updates)
- [Configurar la línea base](https://docs.microsoft.com/es-mx/azure/defender-for-cloud/protect-network-resources)

<hr>

#### Configurar la seguridad del contenedor

- [Configurar el aseguramiento de contenedores](https://docs.microsoft.com/es-mx/azure/defender-for-cloud/defender-for-containers-introduction)
- [Configurar la seguridad de AKS]([https://docs.microsoft.com/es-mx/azure/security/fundamentals/iaas](https://docs.microsoft.com/es-mx/azure/aks/concepts-security))
- [Configurar el registro de contenedores](https://docs.microsoft.com/es-mx/azure/container-registry/container-registry-get-started-portal?tabs=azure-cli)
- [Configurar la seguridad de la instancia del contenedor](https://docs.microsoft.com/es-mx/azure/container-instances/container-instances-vnet)
- [Implementar la gestión de vulnerabilidades](https://docs.microsoft.com/es-mx/azure/defender-for-cloud/deploy-vulnerability-assessment-vm)
