**Future Ready Talent Projects**

**Project Title:**

CSK Fitness Training Gym Website

**Project Description :**

The CSK Gym Website project aims to create an immersive online platform for fitness enthusiasts, providing a comprehensive and dynamic experience for individuals seeking top-notch fitness training. The website will serve as a hub for information, guidance, and community engagement, fostering a sense of motivation and support for users on their fitness journey.  Additionally, our website will feature “Custom Question Answers” powered by Azure Language, an AI service provided by Azure, to help customers with any questions they may have. This will improve the overall experience and make it more enjoyable for our customers. We have used Azure App Service and Azure App Insights to host and manage our website, respectively. We have also integrated an AI chatbot to enhance the overall customer experience.

**Industry Type :**

Lifestyle

**Core Azure Services :**

- **Azure App Service (for hosting the website)**
- **Azure App Insights (to understand the performance and usage of your live web application)**

**Azure AI Services :**

- **Azure Language Services** 
- **Azure Bot Services**

**Web Technologies Used :** 

- **Html**
- **CSS, JavaScript**

**IDE Used :**

- **Visual Studio Code**

**Steps Followed While Deploying :**

1. Built the whole Web Application on the Visual Studio Code.
1. Then Uploaded my WebApp in my GitHub Repository
1. Then Created an Azure APP Service without any code in it.
1. Then Went inside the Created Azure App Service and then to Deployment Center option in Deployment Section of Azure App.
1. Then Selecting the Source as external Source and then pasting the link of my Github repository and Save and sync.
1. Now the Web Application is Successfully Deployed. Click on the Browse option to redirect to our website.
1. Now create the Azure app insights in the same resource group.

**Working Links of Project:**

- **Web Application hosted on Azure** : https://gymtrainer.azurewebsites.net/
- **Project Video url:** [**https://drive.google.com/file/d/1ErERAHSPulAoIZpm_AoiDiiaVkIgtRbK/view?usp=sharing**](https://drive.google.com/file/d/1ErERAHSPulAoIZpm_AoiDiiaVkIgtRbK/view?usp=sharing)

- **Project Documentation url: https://drive.google.com/file/d/1jNyd2-0Q6XwhWpzH_xvr26eo1Z7zEeZs/view?usp=sharing**

**ScreenShots of the project :**

Go to app service-> create a web app-> create resource group-> enter name-> select runtime stack

![Screenshot 2024-01-17 140616](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/7bc92763-80e8-4388-a29f-b6a9da9b7cfb)


select windows plan -> pricing plan -> review + create

![Screenshot 2024-01-17 140638](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/43a0d8c3-0e9d-41fb-b8dd-1b577c939c1a)


This is After deployment

![Screenshot 2024-01-17 141229](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/3f81d593-4e69-4429-a050-b9a4445d783a)


click on deployment center-> select source(external git)-> (copy the repository from the github and paste it) in Repository-> Branch(main)-> click on save

![Screenshot 2024-01-17 141352](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/a1ac073d-10c7-4c3b-ad11-9a81449eb801)


This is our second service that is application insights

![Screenshot 2024-01-17 142837](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/1c51e989-660c-42ec-9b86-e06c04239994)


To connect application insights to the app services go to the app service-> API management-> click on create new

![Screenshot 2024-01-18 190000](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/0d73414c-cea4-4816-866c-f3b4a3de97aa)

Enter the organization name and administrator email

![Screenshot 2024-01-18 190358](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/170657b1-4a9e-4309-89fc-a7f01ad46ee5)

Go to monitoring select the application insights and click in review + create

![Screenshot 2024-01-18 190411](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/d38f99ec-dd70-4f3e-b47d-a4a38fd24015)

Now click on Link API

![Screenshot 2024-01-18 191022](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/72db89ce-107a-44f4-81f1-d746b789d61b)

Select the App service

![Screenshot 2024-01-18 191223](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/1ae6c030-27c0-44fa-98f6-b2cd004e40ec)

Select the app service and click on create

![Screenshot 2024-01-18 191248](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/fa166705-2630-4af8-8040-441b6026b487)

Now Our application insights is linked with the App service

![Screenshot 2024-01-18 191418](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/5c734070-e988-46a4-9841-a891950312aa)

Our third service is AI service, Go to AI service-> Language service-> Click on create

![Screenshot 2024-01-17 143022](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/47394dac-7458-4317-b138-babc8130d1df)

Select resource group and enter the name

![Screenshot 2024-01-17 143516](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/471cb73d-90b0-4ecc-bcc1-a4e2c408e272)

Tick the last option and click on review + create.

![Screenshot 2024-01-17 143532](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/f23e53bd-2373-4c4f-81a3-7cc645c01a0e)

After deployment click on go to resource group

![Screenshot 2024-01-17 143831](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/3bbe3fb4-7044-4150-b511-5c2257140949)

Click on our chatbot

![Screenshot 2024-01-17 144112](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/0e70c4ba-b428-4046-ba48-81b19b9f7a6c)

Click on JSON view -> click on language studio and sign in

![Screenshot 2024-01-17 144220](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/3e964c89-d46c-4c17-96ad-319158f86158)

Fill all the details properly, select the resource group and click on done

![Screenshot 2024-01-17 144344](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/efbaa2f8-5148-412d-9182-7ad9aa6da9b9)

Click on create new and then click on custom question answering

![Screenshot 2024-01-17 144422](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/c23bca87-29a9-44e9-9a31-963ca390f706)

Azure Enter search service name -> azure search location-> azure search pricing tier -> create.

![Screenshot 2024-01-17 144923](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/342a1c78-a9f4-4445-9503-b16f8745e887)

Select the language

![Screenshot 2024-01-17 145226](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/fda5e249-f525-42b7-b8c8-17f11d7ba7ab)

Click on next and create project

![Screenshot 2024-01-17 145359](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/5f40692d-5118-428d-ba5f-dc7b43f52f50)

![Screenshot 2024-01-17 145443](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/b52be04c-7205-45fb-a54e-525b685e5429)

Now upload our all the question and answer pdf you have created 

![Screenshot 2024-01-17 145656](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/ecda253d-c174-44e7-93f4-9d49ed928aa0)

Now go to lnguage studio

![Screenshot 2024-01-17 150406](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/974b5447-5394-4d86-b97a-2889cd2d5297)

Now click  on create a bot

![Screenshot 2024-01-17 150514](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/e3bfcf62-fdc1-43a8-9393-838a43c6d674)

Select resource group-> bot handle

![Screenshot 2024-01-17 151004](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/7915e71f-f7d7-4c91-aae5-2bc23151a0b0)

Enter App name and select SDK language selection then click on next

![Screenshot 2024-01-17 151021](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/9113bac4-bc2f-401a-98cb-1758998b2082)

Fill all the details properly and click on review + create.

![Screenshot 2024-01-17 151033](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/10b88d7c-1eb2-4f13-b2ad-031bcfee60da)

Now our bot is ready 

![Screenshot 2024-01-17 151845](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/e0e77263-5d86-4f40-8f40-66f56c1ef40a)

**ScreenShots of the website after deploying**

![image](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/0c85c9e3-c7fa-4c9e-a85f-e5d53afbadcd)

![Screenshot 2024-01-17 193838](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/1812a355-f65a-4974-92f8-39048629f355)

![Screenshot 2024-01-17 194340](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/79755fd4-1c9b-48df-bacd-fd3ea2080bef)

![Screenshot 2024-01-17 194406](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/ace45c45-c1c7-4b45-80a3-210235712ae6)

![image](https://github.com/SushantPrasad13/Fitness-Training-NeoGym-Website/assets/144934599/eec5b61f-7de1-4f6c-8381-3dd1ae8a180f)















































