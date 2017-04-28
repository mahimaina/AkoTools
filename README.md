# Teachers Toolset

The Teacher’s Toolset is GUI full of tools for teachers to use to create lessons, manage classrooms (groups of students) and manage students individually. 

The GUI below shows the use of the inventory as a Teacher's Toolset. There is an undroppable and unmovable item in the teachers inventory slot [sic] that the teacher uses to bring up the Teachers Toolset. The GUI menu will ensure that teachers do not need to use chat commands or edit config files to effectively and intuitively manage classrooms of up to 36 students. 

#### The GUI menu items are:

##### 1st Level Of GUI Items:

```
/freeze
/unfreeze
/fly
/nofly
/kill
/msg
/tp (to teacher)
```

##### 2nd Level Of GUI Items:

```
/classToggle
/startLesson
/endLesson
/setLesson
/spawnLesson
/resetLesson
/extendLesson
```

The idea behind the use of the Teachers Toolset was for teachers to walk through a Portal on the the boat (Te Waka - See the network plan above) which would boot up a new server. This server would be one of 5 that they are allowed to set up, and be essentially a superflat world, but with a circular border around the outside of unscaleable mountians/cliff faces. 

Once inside the new server they can use the Spawn Lesson GUI item (/spawnLesson) in the Admin menu to create a LESSON, which is a ‘plot’ bordered by Orange Wool blocks (every second block on the border will be Orange Wool). 

The teacher may add/remove blocks from the Lesson area and then use the Set Lesson GUI item (/setLesson) in the Admin menu to save the state of the lesson area in that server. The teacher can then use the Start Lesson GUI item (/startLesson) in the Student and Classroom menu while the are standing inside the lesson boundary to tp/warp all/some of their students in their classroom to that lesson, from another server OR another lesson. The teacher can also use the End Lesson GUI item (/endLesson) in the Student and Classroom menu to tp/warp all/some of their students in their classroom from the lesson, back to Te Waka or to the Lesson server lobby (to be decided).

“When students are in the lesson they cannot move or build beyond this border. There may be several lessons within each server, but students may only be part of one lesson at a time [sic].” 

The lessons can be reset back to the original lesson that the teacher set by using the Reset Lesson GUI item (/resetLesson) in the Admin menu while they are standing in the lesson. This will reset the lesson back to the original saved state it was when the teacher created the lesson using the Set Lesson GUI item (/setLesson) in the Admin menu to save the lesson.

Once a teacher leaves the server the server may only stay open for another 5 minutes. After this time all players inside the server will be warped back to Te Waka and the server will be closed. Only one server at a time may be open by a teacher. If the teacher opens another server (walks through another portal in Te Waka), then any other servers that they have open will immediately close (warping all players back to Te Waka).  

When using the Student and Classroom menu each apple represents a single student. If there are only 5 students in a particular classroom, there will only be 5 apples, if there are 28 students, then 28 apples. There can be a maximum of 36 apples (or students). The teacher can select individual students or several students by clicking on the apples. This will change the apples to Golden apples. Each apple will also have details about each student in the lore including Name, Location (server), and Status (in lesson, free, offline, attached to another teacher). The teacher can also toggle between these selected students and the entire class by using the Class Toggle GUI item (/classToggle) in the Student and Classroom menu. 	
