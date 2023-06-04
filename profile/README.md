<image src='https://github.com/Beach-Combine/.github/blob/main/images/header.png?raw=true' width="800"/>
<br/>

## 📢 Introduction

Do you remember the warm white and soft sandy beach and the blue and transparent but cool sea under the hot sun?

Perhaps there are not many days left to see such a view of the sea. The increasing amount of ocean garbage each year and the coastlines that have become barriers due to this garbage being pushed by the waves have reached an uncontrollable level. The image of the sea that we remember is mostly managed at a huge social cost only during the peak season, and the beaches that are not frequented by people or during the off-season have long been abandoned.

Walking on the sandy beach, one's feet are pierced by rusty nails, and in the water, glass fragments are visible. Unlike well-maintained roads and parks in the city center, the coastline covered with old ropes and Styrofoam, constantly polluted, requires steady and large-scale manpower for cleaning. Currently, the only private cleaning method is beachcombing, an unfamiliar and strange activity that involves directly scraping the coastline and picking up garbage.

This project is an app development project aimed at achieving the UN SDGs goal of "**Life Below Water**" which is one of the sustainable development goals designated by the UN, in line with the spirit of cooperation and coexistence in addressing global issues faced by the UN. Even if it is an impossible goal for one group or individual, if it can be shared and enjoyed as a culture and trend formed throughout society, it is hoped that tens of thousands of 'voluntary' helpers can emerge. The name of our project, Beach-Combine, which means "let's protect the sea by working together," was born this way.

<br/>

## 📲 Execution Method

### For Android User 

1. Download apk file ⭐ [here](https://drive.google.com/file/d/1o0lQqgl7VHFFrbijnl_atLjot7o1Y9GQ/view?usp=sharing) ⭐. (Available for Android version 12 or higher)
2. You can use it right away by installing it on your smartphone!
- Currently, this service is providing beta service for Busan, Korea

### Tip
Our service is currently focused on Busan, South Korea. Therefore, we provide a testing feature for customers in inland areas or those who cannot visit Busan to experience the entire cleaning process.

Upon entering the home screen, users will see a `Test` button. When they press this button, their current location will be moved to the Busan area, allowing them to explore various features. If users move to a different location from their current position, the screen will reflect the corresponding change. Feel free to click on nearby markers to experience different feedback.

Please note that this feature is designed solely for testing purposes and is not reflected in the actual database. Therefore, no rewards will be given upon completing the entire cleaning process. Keep this in mind!

In the actual Busan sea, all features can be used without any issues. Come and enjoy Busan!

<br/>

## ⚙️ Release Note
### 2022-03-31
> v1.0.0 release
### 2022-06-05
> v1.1.0 release
- Added Admin Feature
- Added Testing Feature
- Added Notification Feature
- Added Tutorial Feature

## 💡 How to use

<image src='https://github.com/Beach-Combine/.github/blob/main/images/longImage.png?raw=true' width="800"/>

<br/>

## 📽 Demo Video Link

[![BeachCombine](https://github.com/Beach-Combine/.github/blob/main/images/video.JPG?raw=true)](https://youtu.be/AJusc-HUwQA)

<br/>

## 🏛 Project Architecture

<image src='https://github.com/Beach-Combine/.github/blob/main/images/architecture.png?raw=true' width="800"/>

<br/>

## ✅ Server Deployment Process (CI/CD using Github Actions)

### Local : Gradle build, Docker build
1. jar build : `gradle build`
2. image creation : `docker build -t yourAccountName/repositoryName ./`
3. push to Docker Hub : `docker push yourAccountName/repositoryName`

(`AccoutName` and `RepositoryName` are from Docker Hub)

### Server : Deploy
1. Pull from Docker Hub : `docker pull yourAccountName/repositoryName`
2. Create image as configured in Docker-compose.yml : `docker tag yourAccountName/repositoryName dockerImageName`
3. Run Docker Compose : `docker-compose up`

(`dockerImageName` should be written as the image name in Docker-compose.yml)

<br />

## 🛠 Tech Stacks

<image src='https://github.com/Beach-Combine/.github/blob/main/images/techStack.png?raw=true' width="800"/>

<br/>

## 📁 ERD

<image src='https://github.com/Beach-Combine/.github/blob/main/images/erd.png?raw=true' width="800"/>

<br/>

## ❗ GIT Strategy

### 1) Git Workflow

### main → develop → feature/Issue#-feature, fix/Issue#-feature, refactor/Issue#-feature

1. Work individually on each branch `local - feature/Issue#-feature`
2. After completing the task, submit a PR to `remote - develop`.
3. After code review, receive approval and merge
4. Every time a merge occurs in `remote - develop`, all team members pull from `remote - develop` to maintain the latest status

### 2) Commit Convention

| Tag name | Description                                                 |
| -------- | ----------------------------------------------------------- |
| feat     | Commits that add a new feature                              |
| fix      | Commits that fix a bug                                      |
| hotfix   | Fix an urgent bug in issue or QA                            |
| build    | Commits that affect build components                        |
| chore    | Miscellaneous commits                                       |
| style    | Commits for code styling or format                          |
| docs     | Commits that affect documentation only                      |
| test     | Commits that add missing tests or correcting existing tests |
| refactor | Commits for code refactoring                                |

<br/>

## 📑 Coding Convention

### 1) Naming Convention

- Variables, functions, and class names should use camelCase.
- For functions, use a verb followed by a noun.
  e.g.) getInfo()
- Column names stored in the DB should use snake_case.
  e.g.) member_id
- URL names should use kebab-case, consisting of lowercase nouns.
- Use hyphens (-) as separators, and avoid using separators when possible.
  e.g.) **[www.example.com/user](http://www.example.com/user)**

### 2) Builder

- To improve readability, builders are required instead of constructors

<br/>

## 👥 Contributors

|                                  Mobile/AI                                   |                                    Backend                                    |                                   Backend                                    |                                    Design                                     |
| :--------------------------------------------------------------------------: | :---------------------------------------------------------------------------: | :--------------------------------------------------------------------------: | :---------------------------------------------------------------------------: |
| <img src="https://avatars.githubusercontent.com/u/76910498?v=4" width=150px> | <img src="https://avatars.githubusercontent.com/u/101239440?v=4" width=150px> | <img src="https://avatars.githubusercontent.com/u/83302344?v=4" width=150px> | <img src="https://avatars.githubusercontent.com/u/123039013?v=4" width=150px> |
|                     [김성겸](https://github.com/ksk0605)                     |                     [권보민](https://github.com/pingowl)                      |                   [추서연](https://github.com/ChooSeoyeon)                   |                   [백송은](https://github.com/songeunbaek)                    |

<br/>

## 📎 Link

- Email : [t01053604256@gmail.com](mailto:t01053604256@gmail.com)
- [Mobile repository](https://github.com/Beach-Combine/Mobile)
- [Backend repository](https://github.com/Beach-Combine/Backend)
- [AI repository](https://github.com/Beach-Combine/AI)
  <br/>
