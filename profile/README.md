# Mamasteps

<p align="center"><img src="https://res.cloudinary.com/startup-grind/image/upload/c_fill,dpr_2,f_auto,g_center,q_auto:good/v1/gcs/platform-data-dsc/contentbuilder/GDG-Bevy-ChapterThumbnail.png" height="200px" width="200px"></p>

Project to participate in 2024 google solution challenge

# Member
|Jaegyeong Han|Sungkyu Shin|Gyuhyeok Hwang|Sihyeon Lee |
|:-:|:-:|:-:|:-:|
|-lead, backend|-backend|-backend|-frontend|
|<img alt="h" src="https://github.com/INHAGDSC-stack-overflow/.github/assets/126947828/9ad665a6-dc05-481f-9f70-04d8a6d8b33c" width="100px">|<img width="100" alt="s" src="https://github.com/INHAGDSC-stack-overflow/.github/assets/126947828/8b886570-a9df-4323-a203-b29bdd55673f">|<img src="https://github.com/umc-hackathon-Y/Y-Server/assets/113760409/22148297-a7db-4abd-86cf-952e35e1be61" width="100px" />|<img width="100" alt="l" src="https://github.com/INHAGDSC-stack-overflow/.github/assets/126947828/cdfd0562-4ff3-4e5d-b8f4-5ba4e02c45d7">|
|[@hanjaegyeong](https://github.com/hanjaegyeong)|[@kyu4583](https://github.com/kyu4583)|[@Gyuhyeok99](https://github.com/Gyuhyeok99)|[@tlgusdl03](https://github.com/tlgusdl03)|

# Target UN-SDGs

Good Health and Well-being 


# About our solution

 For our solution, we have chosen the third United Nations Sustainable Development Goal, "Good Health and Well-being - Ensure healthy lives and promote well-being for all at all ages," as our target. The health issues of pregnant women are severe, and while physical exercise for mothers has a positive impact both mentally and physically, very few actually practice it. The lack of physical activity not only demands high costs from the global economy but also significantly impacts individual health, prompting us to set this as our development goal.

 This project is a walking planner developed for expectant mothers to support them in achieving a physically and mentally healthy childbirth. The app provides appropriate walking exercise schedules based on the user's pregnancy progress, activity level, and preferred walking times, and automatically generates suitable walking routes. During this process, it integrates with Google Calendar to manage schedules, facilitating easy adherence to the planned activities.

 # App Demo

여기 추가해줘


# About Implementation
## Backend
### 1. Tech Stack
- Java 17
- Spring, Spring boot
- Spring Web MVC, Spring Security
- Spring Data JPA
- MySQL
- AWS(RDS, Elastic beanstalk, s3, route53, ec2)

### 2. Architecture
<img width="841" alt="아키" src="https://github.com/INHAGDSC-stack-overflow/.github/assets/126947828/04685343-84c4-4391-aa56-51799d46ba69">

### 3. ERD

![erd](https://github.com/INHAGDSC-stack-overflow/.github/assets/126947828/79029d03-d54d-42c2-a016-e31ea44006b7)

## Frontend
### 1. Tech Stack

여기 모릅니다

### 2. Architecture

여기 모릅니다

- We chose MVC pattern as an architecture.
  - Every feature is divided into modules, and each module has its own controller, view, and binding.
- The data layer is divided into models and providers. 
  - The models are used to store data, and the providers are used to communicate with the backend.
- We used the Google Maps Flutter plugin to implement the map feature. We also used the Google Login plugin to implement the login feature.
