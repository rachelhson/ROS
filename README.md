# Rachel ROS Tips 
Some ROS tips to use 
1. Source devel setup 
   ~/catkin_ws/devel/$ vim ~/.bashrc
   `source /opt/ros/kinetic/setup.bash`
   `source ~/catkin_ws/devel/setup.bash`
   make sure above two lines in vim 
    * For vim `i` - insert 
              `esc` + `:wq` Save and close 
              
rostopic pub `rosmsg type`


history | grep pub 

`pub` what you are looking for 

exclud grep -v 

history | grep -v 'pub'

## record everything happening in topic 
rosbag  record / `rostopic name`

replay 
rosbag play `the file` 

## control terminal window 

rosrun- `&` rosrun

use `bg` / `fg` ( background and forward ground) 
`jobs` show the what is running on the command 

`screen`

`ctrl+shift+t`
`ctrl+a` ; cursor goes to the first place on the command 

`env` shows the what variable 

~ = $Home directory 


- conneting simulation to real robot ( controller ) 
