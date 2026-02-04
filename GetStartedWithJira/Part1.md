# Part 1: Project Overview

## Few words about Jira
* **Jira Core** – the basic platform. A simple, intuitive system for managing teamwork in any department,
* **Jira Software** – SCRUM and Kanban boards, Agile reporting, work schedule (thanks to an additional Portfolio plugin). Jira also allows you to use combined methods for both boards, i.e., working within a mixed methodology called Kanplan. Similar to Scrumban, this methodology combines features of both Scrum and Kanban. Kanplan is ideal for teams that want to have a backlog but do not want to work in sprints.,
* **Jira Service Desk** - dedicated to teams that handle internal or external customer requests on a daily basis, with the ability to measure and report on SLAs,

## Amenities on Coursera
* If you have some questions, you can participate in [Community Discussion Forum](https://www.coursera.support/s/topic/0TO8W000001WkgnWAC/business?language=en_US),
* If you are looking for documentation, you can go to [Learner Help Center](https://www.coursera.support/s/learner-help-center).

## Few words about Agile framework
An agile framework incorporates elements of continuous planning, testing, integration, and other forms of continuous development. Agile frameworks are lightweight compared to traditional development methods, which means that rules and practices are kept to a minimum.

<img src="https://github.com/98Miquelle11/jira/blob/main/images/1.jpg?raw=true" width="900">

* **Scrum** - breaks down big projects into small tasks that can be completed in short development cycles,
* **Kanban** - a methodology to organize work using the board and moving the tasks along the board.
* **Crystal** -  is used for short-term projects involving teams located in the same workspace. There are no firm rules to follow with this approach.,
* **Dynamic Systems Development Method (DSDM)** - project management and product delivery method used by large organizations. DSDM follows disciplined processes for a strong governance foundation.,
* **Feature-Driven Development** - FDD is laser focused on the development team. Unlike other frameworks, FDD requires thorough documentation and strict organization.

## Get started with Jira lab
### Instructions
In this Guided Project, you will have access to a virtual workspace with all required software pre-installed. You’ll be given video or text-based instructions - the tasks shared above - that you can complete in your workspace.

You can refer [here](https://www.coursera.support/s/article/learner-000001247) for more information.

### 1. Create a project and choose framework
In this first task we are going to create free Jira account, a project and choose framework
to get started with our agile work.

1. Go [here](https://www.atlassian.com/software/jira) and create an account - click **Get it free**,
2. Sign up by putting you email (then add any name and surname) oraz continue with one of the options,
3. Follow the procedure of loggin in,
4. For **Our products** click **Jira Software**,
5. When you are logged in and on a homepage - `https://www.atlassian.com/software/jira`, click **Get it free**,
6. Don't choose any other product and click **Next**,
7. Create tyour first project - create your project site by giving **Your site** a unique name. Then click **Agree**.
8. Yo will be asked for tools you are using or area of work you are working. It is possible they will be asking you varius questions.,
9. After that, you have to select a template to get started. Select **Kanban** - it's better for flexible type of work (Scrum is more directed to tighter deadlines and time management).
10. Choose**Task** as one of types of work you need - you can change it later.
11. You will have default statuses. Leavit and click **Finish**. After everything, your display should look like this:

<img src="https://github.com/98Miquelle11/jira/blob/main/images/2.jpg?raw=true" width="900">

### 2. Set up a Kanban board
In this task we are going to set up our Kanban board and, in the process, learn a little bit more about agile methodologies.

#### Theory
Under project name, you cane see horizontal Sections tab:
- **Timeline** - you can plan the time management of your project and plan all the different things that we need to achieve in time,
- **Board** - Kanban board is the core of our task management,
- **Code** - for admission. You can connect your Jira to your GitHub accunt. Connecting GitHub to Jira allows you to view development activity in the context of your Jira project and issues. To send development data from GitHub to Jira, your team must include issue keys in branch names, commit messages, and pull request titles.,
- **Pages** - we can use them as online materials, online published pages that we can share with our team for information about our project or progress.

Some agile methodologies are using **Sprint** work, so they are organizing the work in certain time frames, where everything is pushed forward the Sprint and then things are evaluated and reorganized - and then new Sprint comes. This is very good for tight deadlines and tight time management (Scrum is good for such environment). But when it comes to more fluid time of management when we don't really need too necessarily organized sprints, **Kanban** is better.

#### Let's set up our Canban board!
A Kangan board works in columns, so we need to arrange and personalize our columns. Right now our system is providing us with the "TO DO", "IN PROGRESS" and "DONE" columns. We need to organize this base on our own way of working, in our own processes.

1. Click **In progress** and change it to **Development**. Change **Done** to **Deployed**.,
2. Click **+** on the right to add one more column. Set its ame to **Peer review**. You can click and move this column to anywhere. Put it between **Development** and **Deployed** columns.,
3. Create another column and name it **Test** and move it before **Deployed** column. After collapsing sidebar your display should look like this:

<img src="https://github.com/98Miquelle11/jira/blob/main/images/3.jpg?raw=true" width="1100">

### 3. Create issues
In this task we are going to create issues. Let's say we are software development team that needs to deploy the phone functionalities, our mobile system - phone calls, contact management, speed dial etc. We will write a number of issuues, so things that need to be done.

1. In "To do" column write **Dialer** and click ENTER. You can see your issue have unique identifier.
2. Create **Call hisotry**, **Contacts (add)**, **Contacts (read)**, **Speed dial**, **Add favorites**.
3. Click one of the issues, click **Settings** icon on a "Details" tab, then **Manage fields**. You can choose what do you want to display for each of your issue by type.

<img src="https://github.com/98Miquelle11/jira/blob/main/images/4.jpg?raw=true" width="1000">

Here you can edit what type of information do you want to see in each of these issue types. We want to catch **Summary** and **Description** - "Descripton fields". We have **Status**, **Assignee** and **Labels** fields in "Context fields" (**Reporter** is currently hidden - you can drag and drop it if you want to show it in your "Context fields").

On the left sidebar you can see:
* **Task** - short defined actions,
* **Subtask** - pieces of work can be broken down in even more granular steps,
* **Epic** - large body of work that is broken down into smaller user stories for incremental delivery.

On the left sidebar you can see more fields to add to your **Dexcription** and **Context fields**. 

4. Click **Create a field**, choose **Date**, name it *Assigned date* and move it to **Context fields**,

So an issue is essentially anything that the teams needs to work on - in our case something to develop. However it might be a bug problem.

====== 4:00 ===============

5. Click **Save changes** and get back to project Board.

You have created a number of issues that we know are features to develop or portions of features to develop. That 
will help us achieve a certain user function, for example dial phonecall, managing the call history, adding context etc. 

We could define the context as one single tasks and then having the functions of adding contact or reading contacts. They could be marked as **subtasks**. Also a dialer could 

### Final outcome of a project
We created an agile software project, we used the Kanban framework (Kanban board). We created different tasks grouped under an Epic and we learned what tasks, the stories or epics in an agile framework are. We created the board (we needed to develop the phone activity of the phone app or system), then devised the actions in different tasks. We created steps and workflow: different four columns to signify how the tasks are moving throughout the development process.

We created a Timeline: we established frameworks and timeframes to work with the different development tasks and group them under one single Epic. So an overarching piece of development that will contain different tasks that are grouped by the same functionality, scope and objective. We learned hot to group the issues or tasks under a single Epic, choosing
form existing tasks or creating new ones.

We learned how to invite team members and assign different steps of development to each of them. We learned how to edit your workflow. 

Within a specific issue or a specific task that is grouped under an Epic, we learned how to edit the workflow - we can create a linear process whenever we need it, establishing mandatory transitions or changes in status between one area and the next. So we learned how to edit our workflow the way we prefer, rather than using simply the workflow that the system presents us at the moment of creation of the project.
