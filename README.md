# Nebula API

[Headers](#headers)

[Authentication](#authentication)

[RPC API](#rpc-api)

[Routes](#routes)
* [Users](#users)
  + [Create user](#create-user)
  + [Update user](#update-user)
  + [Get user](#get-user)
  + [Get users](#get-users)
  + [Delete user](#delete-user)
* [Projects](#projects)
  + [Create project](#create-project)
  + [Update project](#update-project)
  + [Get project](#get-project)
  + [Get projects](#get-projects)
  + [Get project users](#get-project-users)
  + [Create project role](#create-project-role)
  + [Create project user](#create-project-user)
  + [Delete project user](#delete-project-user)
  + [Delete project](#delete-project)
* [Platforms](#platforms)
  + [Create platform](#create-platform)

## Headers

```
Content-Type: application/json
```

## Authentication

```
Basic Auth
```

## RPC API

All RPC API calls are HTTP POST requests.
And all URLs have the format:

`http[s]//:host/:api_version/rpc/:function_name`

There can be different versions of a function with the same API verision,
usually denoted by `:function_name_:version`.
This is reserved for backwards compatibility.

## Routes

The route documentation omits the URL host property.

### Users

#### Create User

`POST /v1/rpc/create_user`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Update User

`POST /v1/rpc/update_user`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get User

`POST /v1/rpc/get_user`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Users

`POST /v1/rpc/get_users`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Delete User

`POST /v1/rpc/delete_user`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

### Projects

#### Create Project

`POST /v1/rpc/create_project`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Update Project

`POST /v1/rpc/update_project`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Project

`POST /v1/rpc/get_project`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Projects

`POST /v1/rpc/get_projects`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Project Users

`POST /v1/rpc/get_project_users`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Create Project Role

`POST /v1/rpc/create_project_role`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Create Project User

`POST /v1/rpc/create_project_user`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Delete Project User

`POST /v1/rpc/delete_project_user`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Delete Project

`POST /v1/rpc/delete_project`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

### Platforms

#### Create Platform

`POST /v1/rpc/create_platform`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Update Platform

`POST /v1/rpc/update_platform`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Platforms

`POST /v1/rpc/get_platforms`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Delete Platform

`POST /v1/rpc/delete_platform`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

### Hosts

#### Update Host

`POST /v1/rpc/update_host`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Upsert Hosts

`POST /v1/rpc/upsert_hosts`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Update Host Data

This is user data for a host.

`POST /v1/rpc/update_host_data`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Filter Hosts

`POST /v1/rpc/filter_hosts_v4`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Hosts

`POST /v1/rpc/get_hosts`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Host

`POST /v1/rpc/get_host`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Delete Host

NOTE: TBA

`POST /v1/rpc/delete_host`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

### Host Groups

#### Get Host Group

`POST /v1/rpc/get_host_group`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Host Group Item Count

`POST /v1/rpc/get_host_group_item_count`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Host Groups

`POST /v1/rpc/get_host_groups`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Host Group Items

`POST /v1/rpc/get_host_group_items_v4`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Filter Host Group

`POST /v1/rpc/filter_host_group_v4`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Create Host Group Selected

`POST /v1/rpc/create_host_group_selected`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Create Host Group Item

`POST /v1/rpc/create_host_group_item`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Create Host Group Items

`POST /v1/rpc/create_host_group_items_v2`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Update Host Group

`POST /v1/rpc/update_host_group`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Host Filter

`POST /v1/rpc/get_host_filter`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Create Host Group Filtered

`POST /v1/rpc/create_host_group_filtered`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Update Host Filter

`POST /v1/rpc/update_host_filter`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Delete Host Group Items by Host

`POST /v1/rpc/delete_host_group_items_by_host`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Delete Host Group Item

`POST /v1/rpc/delete_host_group_item`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Delete Host Group

`POST /v1/rpc/delete_host_group`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

### Runbooks

#### Create Runbook

`POST /v1/rpc/create_runbook`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Update Runbook

`POST /v1/rpc/update_runbook`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Runbooks

`POST /v1/rpc/get_runbooks`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Page Runbooks

`POST /v1/rpc/page_runbooks`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Runbook

`POST /v1/rpc/get_runbook`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Delete Runbook

`POST /v1/rpc/delete_runbook`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

### Agents

#### Get Agents

`POST /v1/rpc/get_agents`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

### Jobs

#### Get Job

`POST /v1/rpc/get_job`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Jobs

`POST /v1/rpc/get_jobs`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Delete Job

`POST /v1/rpc/delete_job`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Job Results

`POST /v1/rpc/get_job_results`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Tasks

`POST /v1/rpc/get_tasks`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Work

`POST /v1/rpc/get_work`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

### Cvars

#### Create Cvar

`POST /v1/rpc/create_cvar`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Update Cvar

`POST /v1/rpc/update_cvar`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Cvars

`POST /v1/rpc/get_cvars`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get Cvar

`POST /v1/rpc/get_cvar`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Delete Cvar

`POST /v1/rpc/delete_cvar`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

### Cron

#### Create Job Schedule

`POST /v1/rpc/create_job_schedule`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Update Job Schedule

`POST /v1/rpc/update_job_schedule`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Delete Job Schedule

`POST /v1/rpc/delete_job_schedule`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Pause Job Schedule

`POST /v1/rpc/pause_job_schedule`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Resume Job Schedule

`POST /v1/rpc/resume_job_schedule`

Request
```javascript
{"foo": "bar"}
```

Response
```javascript
{"status": "success"}
```

#### Get User

`POST /v1/rpc/get_user`

Request
```javascript
{"foo": "bar"}
```
NOTE: some notes.

Response
```javascript
{"foo": "bar"}
```
