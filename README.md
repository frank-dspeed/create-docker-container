create-docker-container
=======================

Is Able to ADD/Create Docker Containers and Create/ADD a Config for Services like: NGINX HAProxy, Redis (HIPACHE)


cdc image container_name nginx url

run service mysql apache php5 phpmyadmin sshd

run service hipache redis sshd

run service haproxy sshd

run service nginx php5-fpm sshd

run service nodejs sshd

run service python sshd


CONTAINER NAMING CONVENTION
name_run_service_service_service
 Create SSH User and Container Script
 sshd on h1 and user name@h1 shell script that does ssh into the container from costumer


 addzser Container_NAME Create Run Container Container_name
 install sshd configure it 
 Create Script container_name user that has Credentials for the container and updates IP On Login. ??? make sure only one ssh session runs at once
 
 // argv to get
 foreach ($argv as $arg) {
    $e=explode("=",$arg);
    if(count($e)==2)
        $_GET[$e[0]]=$e[1];
    else   
        $_GET[$e[0]]=0;
}
 
 
$array = array('lastname', 'email', 'phone');
$comma_separated = implode(",", $array);

echo $comma_separated; // lastname,email,phone

// Leere Zeichenkette wenn leeres Array genutzt wird
var_dump(implode('hello', array())); // string(0) ""

 
 take parms --name bob --services name name name --url wiwak.local
 $user = bob_name_name_name
 $services = array(
  "",
  "name"
 );
 adduser ssh_$user
 
 deploy based on name split on _run_ explode on _

