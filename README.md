# Live Project

## Introduction

  For the last two weeks of my time at The Tech Academy, I worked with my peers on a team based project building a content management system for a Theater using C# with the .NET Framework. Building this full scale MVC application was a great learning opportunity for working with a legacy codebase, debugging, cleaning up code, and adding requested features. We utilized Git for our version contorl where we would clone the master to our local system, branch off and add code then commit our changes, push them and create pull request for the owner to lookover and accept. Occasionaly we'd have to deal with merge conflicts that taught us how to resolve said issues by comparing whats new to the master branch and is conflicitng with our working branch. We managed our entire project through Azure and utilized in house features within the IDE Visual Studio. I worked on several back end stories that taught me how to connect a database to communicate with a website in order to store data from users and admins. As well as adding CRUD functionality to affect the data. There were also many front end stories and UX improvements that came with the project. Needing to update or create new code and add css for a modernized website. Over the two week sprint we utilized agile and scrum methodologies where we'd have daily standups and a code retrospective each Friday. Teaching me the skills of time management, the software development life cycle, continuous integration and development. This project honed and gave me more confidence in my skills that I will implement on future projects.

Provided below are descriptions of the stories I worked on, along with code snippets and navigation links. 

## Back-End Stories
- [Create Entity Model and CRUD Pages](#Create-Entity-Model-and-CRUD-Pages)
- [Photo Storage and Retrieval](#Photo-Storage-and-Retrieval)

### Sign-in-page

### Create Entity Model and CRUD Pages

### Photo Storage and Retrieval

*Jump to: [Front-End Stories](#Fronte-End-Stories), [Back-End Stories](#Back-End-Stories), [Skills Learned](#Skills-Learned), [Top Page](#Introduction)*

## Front-End Stories
- [Sign-In-Page](#Sign-in-page)

- `//returns number of people Signed in
//function signInList() {
//    var divList = document.getElementById("PersonList");
//    var names = divList.getElementsByTagName("p").length;
//    document.getElementById("NumPersons").innerHTML = names; 
//}

//Jquery version returning number of people signed in
function signInList() {
    var divList = $("#PersonList p");
    $("#NumPersons").html(divList.length);
}
signInList();`

- [Style Create & Edit Pages](#Style-Create-&-Edit-Pages)
- [Style Index Page](#Style-Index-Page)
- [Style Details & Delete Pages](#Style-Details-&-Delete-Pages)

### Sign-in-page

### Style Create & Edit Pages

### Style Index Page

### Style Details & Delete Pages

## Skills Learned
-
-
-

