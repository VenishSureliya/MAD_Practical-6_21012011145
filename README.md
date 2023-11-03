# MAD_Practical-6_21012011145

Study: Service, Types of Service, Drawable Icon Add in project, MediaPlayer, Add Raw folder, Add mp3 song in raw folder

AIM: What is Service? Write down types of Service. Create an MP3 player application by using service by following below instructions.

Create MainActivity and design according to shown in below image.

Create Service Class and implement MediaPlayer Object

Ans:

"service" refers to a specific component or functionality within a mobile app that runs in the background, independently of the app's user interface, to perform tasks or provide functionality

Types of Services:

1-Background Service:

Background services run continuously in the background, even if the user is not actively using the app. They are often used for tasks like downloading or syncing data, playing music, or checking for updates. ex:Music Player App(notification of the current song)

2-Foreground Service:

Foreground services are used when an app needs to perform a task that the user is aware of and interacting with. They have a higher priority and show a persistent notification to the user, ensuring that the user knows the app is actively performing a task. ex:Developers should not access location informations from the background

3-Bound Sevice:

 client-server interface that allows components(Activity, content provider and service can bind to the Bound service) to interact with the service, send requests, receive results, and even do so across processes with interprocess communication (IPC).  no own lifecycle

![WhatsApp Image 2023-10-01 at 14 40 33](https://github.com/Rohan3429/MAD_Practical-6_21012011103/assets/98172369/967bbb90-516b-42d4-8968-44430d49643f)

