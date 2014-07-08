timetracking
============

Logging of time spent on tasks

Recording time
--------------

To record time you've spent on a task then write a commit message with any of the options below.
```
{
  project: {
        "name": {
                "description": 
                "The name of the overall project being worked on; should have it's own repo"
        },
        "feature": {
                "description": 
                "If you're working on a feature within the project, then name it in this field"
        },
  time: {
        "description": 
        "estimated time spent on this task. Unit is hours. Min value is 0.5 hour",
  "activity": {
        "description": 
        "One of the company defined activities: s/w dev, biz dev, etc."
        },
        "area": {
                "description": 
                "One of the pre-defined phases for the parent activity, 
                e.g. Development->coding or Development->planning"
                }
```

Pre-defined Field Values
----------------

### activity
* s/w development = sd
* biz development = bd
* biz admin = ba


### activity / sub-activity
* s/w development [sd] / planning [p]
* s/w development [sd] / coding [c]
* s/w development [sd] / deployment [d]
* s/w development [sd] / meeting [m]
* s/w development [sd] / testing [t]
* s/w development [sd] / maintenance or bug-fixing [b]
* biz development [bd] / meeting [m]
* biz development [bd] / proposal development [p]


TODO: Write a client app to parse and display this info.
