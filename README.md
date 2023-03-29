# pintool installation and call trace(pintool)
in this repository you will find about the using of pin tool and installation of call trace which is a pin tool


``to have the call trace you need to have a pin tool version in your device

- to have pin tool you need to go through the given tool
- the given link has source of the pin tools (INTEL)


[(https://software.intel.com/content/www/us/en/develop/articles/pin-a-dynamic-binary-instrumentation-tool.html).](url)

- note that the download should be done according to the os(Operatin System)
- now unzip or extract the file of the pintool 
- and now use the commands given below to acccess the pin tool

`cd ''here enter the pintool name("folder name)''`

(here i am working on the linux system so the commands are according to that)

`make`


`make all`

- now the pin tools are added into the pintool folder
-now use the following commands to get the pin tools for the executable files(bengin , malware,ransomware)


`cd source`


`cd tools`


`cd Manual Examples`

- by doing  following commands you get the below following tools such as

1. pinatrace
2. inscount 
3. starce

   `make`
   
   
     `make all`
 

- now  again go through the Simple Example files to get the Call trace pin tool 
- now open a new terminal

`cd pin(floder name)`


`cd source`


`cd tools`


`cd Simple Examples`


`make `


`make all`


- by doing the following commands you get the call tarce pintool
- which is used for retriving the native api invocation sequence
