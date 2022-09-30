# Reading-note-rd13
<hr>

Local Storage and How To Use It On Websites
Why would a developer use local storage for a web application?

The main problem with HTTP as the main transport layer of the Web is that it is stateless. This means that when you use an application and then close it, its state will be reset the next time you open it. If you close an application on your desktop and re-open it, its most recent state is restored. This is why, as a developer, you need to store the state of your interface somewhere. Normally, this is done server-side, and you would check the user name to know which state to revert to.
What information should not be stored in local storage?

In other words, any authentication your application requires can be bypassed by a user with local privileges to the machine on which the data is stored. Therefore, it's recommended not to store any sensitive information in local storage.
Local storage can store what type of data? How would you convert it to that type before storing?

LocalStorage is a key/value datastore that's available on a user's browser. Like cookies, LocalStorage can only store string data for its keys and values. The datastore is only accessible to JavaScript within that domain. Many browser extensions store their data in the browser's so-called Local Storage, which is nothing else than a storage location managed by the web browser. And as the same suggests, all is saved locally on the machine where the browser is installed. Local storage is not in the cloud.
