# Azure Blob Storage and RBAC lab

## 📌 Project Overview

This project demonstrates the implementation of Azure Role-Based Access Control (RBAC) within an Azure Storage environment. The lab simulates real-world enterprise access management scenarios by deploying Azure Blob Storage resources and assigning granular permissions using Microsoft Entra ID identities.

The environment was built by creating a dedicated Azure Resource Group to organize resources logically. A Standard Azure Storage Account using Locally Redundant Storage (LRS) was deployed in the West Europe region. Within the storage account, a private blob container named **lab-container** was created to store uploaded files securely.

To demonstrate identity-based access control, a secondary user account (**admin.user**) was assigned permissions using Azure RBAC. At the storage account level, the **Storage Blob Data Reader** role was assigned, allowing read-only access to blob data. This configuration demonstrates the **principle of least privilege**, ensuring users receive only the permissions necessary to perform their tasks.

Additionally, container-level RBAC was implemented by assigning the **Storage Blob Data Contributor** role directly to the **lab-container** resource. This demonstrates granular permission scoping, enabling administrators to control access at a specific container level instead of across the entire storage account.

This project highlights practical Azure administration skills including storage deployment, container management, RBAC configuration, permission scoping, and resource organization. 

<img width="1906" height="911" alt="Image" src="https://github.com/user-attachments/assets/67722288-b23f-42d5-95c6-34a318c30f19" />
<img width="1910" height="918" alt="Image" src="https://github.com/user-attachments/assets/6d4cf79b-d8d7-4748-b69f-7e53279e059c" />
<img width="1911" height="906" alt="Image" src="https://github.com/user-attachments/assets/4a655d6d-9b55-461e-ae10-a2a1f90bd11b" />
<img width="1907" height="909" alt="Image" src="https://github.com/user-attachments/assets/2a3334ff-b4e6-432c-904b-02955247301e" />
<img width="1913" height="916" alt="Image" src="https://github.com/user-attachments/assets/5d6dc7e6-d505-4a60-993c-e58c134deecd" />
<img width="1911" height="907" alt="Image" src="https://github.com/user-attachments/assets/41ea8354-7687-4f13-99eb-b5deeb240585" />
<img width="1906" height="913" alt="Image" src="https://github.com/user-attachments/assets/0b03bb62-171d-4f97-8947-bf89bf9d1d32" />
<img width="1914" height="903" alt="Image" src="https://github.com/user-attachments/assets/04b8f07f-be9a-43e4-be22-eda7a93e5344" />
<img width="1912" height="905" alt="Image" src="https://github.com/user-attachments/assets/1af088df-f5eb-43f6-bca6-7aade5fefe17" />
<img width="1910" height="911" alt="Image" src="https://github.com/user-attachments/assets/ec1143a1-d7d0-49fb-8d3a-8945f2be9c4b" />
<img width="1910" height="909" alt="Image" src="https://github.com/user-attachments/assets/4e5748e1-8abf-4881-971e-0b091bbd208e" />
<img width="1913" height="910" alt="Image" src="https://github.com/user-attachments/assets/ede27c66-239c-4681-bc65-8641eac192e2" />
<img width="1911" height="906" alt="Image" src="https://github.com/user-attachments/assets/c18c8908-3630-4c6c-aef7-70959c886872" />
<img width="1909" height="912" alt="Image" src="https://github.com/user-attachments/assets/26e41d76-ea83-4e8f-bbcd-5b45bb2b5dbe" />
<img width="1907" height="909" alt="Image" src="https://github.com/user-attachments/assets/c7c7e7c0-7f9d-4a98-b568-9946c3f2987a" />
<img width="1910" height="908" alt="Image" src="https://github.com/user-attachments/assets/cda9f371-468f-4d4f-8fac-97aa5ec93adf" />

