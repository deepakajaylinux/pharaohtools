Methodologies in usage:
-----------------------

Here, let us see how to use the commands under the tool and its usage.

if you simply type the following command,

    phlagrant

As shown in the below screenshot, you will get the display of all the modules available under this tool.

     kevells@Corp:/# phlagrant 

    ******************************
    Pharaoh Tools - Phlagrant
  


    Phlagrant by Golden Contact Computing
    -------------------
      
    About:
    -----------------
    Phlagrant is for controlling Virtual Machines in Development Environments.
    
    -------------------------------------------------------------

    Available Commands:
    ---------------------------------------

    AutoSSH - AutoSSH - Use your Papyrus details to automatically SSH or SFTP into your Phlagrant box
    Box - Box - Manage Base Boxes for Phlagrant
    Destroy - Destroy - Stop a Phlagrant Box
    Flirtify - Phlagrant Flirtify - Generate a Phalgrantfile
    Halt - Halt - Stop a Phlagrant Box
    Invoke - SSH Invocation Functions
    PharaohTools - Pharaoh Tools Provisioner Integration
    Provision - Provision - Stop a Phlagrant Box
    Resume - Resume - Stop a Phlagrant Box
    SFTP - SFTP Functionality
    Shell - Shell Provisioner Integration
    Status - Status - Stop a Phlagrant Box
    SystemDetection - System Detection - Detect the Running Operating System
    Up - Up - Create and Start a Phlagrant Box
    Virtualbox - Virtualbox Provider Integration

    ******************************


Help command:
-------------

It's simple to use the help command,

  phlagrant ModuleName help

This command helps you how the particular modules works, and also about what are the actions it can perform.
The below screenshot explains you how the help command is used to explain the module Box.

    root@deepak-Inspiron-N4010:~# phlagrant AutoSSH help

  ******************************
    Pharaoh Tools - Phlagrant
  ******************************


    This command allows you to autoSSH a phlagrant box

    AutoSSH, auto-ssh, autossh, ssh, SSH

        - cli
        Open an SSH Cli to your Phlagrant Box
        example: phlagrant auto-ssh cli --yes --guess

        - sftp-put
        SFTP Put a file on to your Phlagrant Box
        example: phlagrant auto-ssh sftp-put --yes --guess --source=/path/to/source --target=/path/to/target

        - sftp-get
        SFTP Get a file from your Phlagrant Box
        example: phlagrant auto-ssh sftp-get --yes --guess --source=/path/to/source --target=/path/to/target

    ------------------------------
    End Help
******************************

