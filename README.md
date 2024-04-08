# Project 7 - Task App

Submitted by: **Jasmine Ben-Whyte**

**Task App** is an app that lets users create tasks and populate a calendar with created tasks

Time spent: **1.5** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] App displays a list of tasks
- [x] Users can add tasks to the list
- [x] Session persists when application is closed and relaunched (tasks dont get deleted when closing app) 
  - [x] Note: You have to quit the app, not minimize it, in order to see the persistence.
- [x] Tasks can be deleted
- [x] Users have a calendar view via navigation controller that displays tasks	


The following **additional** features are implemented:

- [x] Tasks can be toggled completed
- [x] User can edit tasks by tapping on the task in the feed view

## Video Walkthrough

<div>
    <a href="https://www.loom.com/share/5080ec9af0ac4fc99ae19bb30aaf1fe8">
      <p>Task App - Watch Video</p>
    </a>
    <a href="https://www.loom.com/share/5080ec9af0ac4fc99ae19bb30aaf1fe8">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/5080ec9af0ac4fc99ae19bb30aaf1fe8-with-play.gif">
    </a>
  </div>

## Notes

At first, when a task when ticked off as completed, it would just repopulate on the task list after been updated on the UI interface to a completed task. This was due to the id element of the Task instance was changing each time the same instance was referenced for updating, so I had to correct the logic so that the id was initialized within the init method of the struct rather than being initialized in the code body of the Task struct.

## License

    Copyright [2024] [Jasmine Ben-Whyte]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
