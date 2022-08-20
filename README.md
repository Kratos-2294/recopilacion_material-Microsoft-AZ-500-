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
- [Configurar la seguridad de AKS](https://docs.microsoft.com/es-mx/azure/aks/concepts-security)
- [Configurar el registro de contenedores](https://docs.microsoft.com/es-mx/azure/container-registry/container-registry-get-started-portal?tabs=azure-cli)
- [Configurar la seguridad de la instancia del contenedor](https://docs.microsoft.com/es-mx/azure/container-instances/container-instances-vnet)
- [Implementar la gestión de vulnerabilidades](https://docs.microsoft.com/es-mx/azure/defender-for-cloud/deploy-vulnerability-assessment-vm)

<hr>

#### Implementar la seguridad de administración de recursos de Microsoft Azure

- [Crear bloqueos de recursos de Microsoft Azure](https://docs.microsoft.com/es-mx/azure/azure-resource-manager/management/lock-resources?tabs=json)
- [Administrar la seguridad del grupo de recursos](https://docs.microsoft.com/es-mx/azure/role-based-access-control/overview)
- [Configurar políticas de Microsoft Azure](https://docs.microsoft.com/es-mx/azure/governance/policy/tutorials/create-and-manage)
- [Configurar funciones de RBAC personalizadas](https://docs.microsoft.com/es-mx/azure/role-based-access-control/custom-roles)
- [Configurar permisos de suscripción y recursos](https://docs.microsoft.com/es-mx/azure/role-based-access-control/role-assignments-portal?tabs=current)

<hr>
<hr>

### Administración de operaciones de seguridad (25-30 %)
<hr>

#### Configurar servicios de seguridad

- [Configurar Microsoft Azure Monitor](https://docs.microsoft.com/es-mx/azure/azure-monitor/overview)
- [Configure Microsoft Azure Log analytics](https://docs.microsoft.com/es-mx/azure/azure-monitor/logs/manage-access?tabs=portal)
- [Configurar el registro de diagnóstico y la retención de registros](https://docs.microsoft.com/es-mx/azure/azure-monitor/essentials/platform-logs-overview)
- [Configurar el escaneo de vulnerabilidades](https://docs.microsoft.com/es-mx/azure/defender-for-cloud/deploy-vulnerability-assessment-vm)

<hr>

#### Configurar políticas de seguridad

- [Configure la administración centralizada de políticas mediante Microsoft Defender for Cloud](https://docs.microsoft.com/es-mx/azure/defender-for-cloud/tutorial-security-policy)
- [Configure el acceso justo a tiempo mediante Microsoft Defender for Cloud](https://docs.microsoft.com/es-mx/azure/defender-for-cloud/just-in-time-access-usage?tabs=jit-config-asc%2Cjit-request-asc)

<hr>

#### Administrar alertas de seguridad

- [Crear y personalizar alertas](https://docs.microsoft.com/es-mx/azure/defender-for-cloud/defender-for-cloud-introduction#custom-alert-rules-preview)
- [Revisar y responder a alertas y recomendaciones](https://docs.microsoft.com/es-mx/azure/defender-for-cloud/managing-and-responding-alerts)
- [Configurar un playbook para un evento de seguridad mediante Microsoft Defender for Cloud](https://docs.microsoft.com/es-mx/azure/defender-for-cloud/workflow-automation)

<hr>
<hr>

### Protección de datos y aplicaciones (25-30 %)
<hr>

#### Configurar políticas de seguridad para administrar datos

- [Configurar la clasificación de datos](https://docs.microsoft.com/es-mx/azure/information-protection/what-is-information-protection)
- [Configurar la retención de datos](https://docs.microsoft.com/es-mx/azure/azure-monitor/logs/data-retention-archive?tabs=portal-1%2Cportal-2)

<hr>
