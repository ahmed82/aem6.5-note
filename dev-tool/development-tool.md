
## Content Packages - Immutable

* Immutable

1. Code persisted in repository (/apps) can be checked into Git and deployed
through Cloud Manager
1. Code should never be deployed directly on dev, stage and prod environment

 Example: OSGi Configuration should be committed to source control rather than
managed at runtime via Web Console's configuration manager


## Content Packages - Mutable

* Mutable content typically committed into Maven archetype-based AEM project

Content includes:

1. Services users

1. Folders

1. Node types

1. Editable templates

1. Script


## Content Package Structure

* Deployments must have single Experience Manager package
* Inside package: code, configuration, baseline content
* Single content package cannot deploy to both /apps and runtime-writable areas
(/content, /conf, /home and so forth) of repository
* Immutable areas: /apps and /libs
* Mutable areas: everything else

![image](https://github.com/user-attachments/assets/94f045f0-b3c1-48aa-9fb7-cb84074f4b42)
![image](https://github.com/user-attachments/assets/731bdf1c-a24f-4c10-b356-9d8eb8866daa)
![image](https://github.com/user-attachments/assets/260671f5-25aa-46ed-97f5-dabe31e38f22)
![image](https://github.com/user-attachments/assets/f65064b0-a163-4687-8e1b-23c30f7e6f04)


