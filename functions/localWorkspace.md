# The Local Workspace
The principle is simple: a folder is created on the device in which the latest changes are automatically saved. This allows you to work on multiple presentations simultaneously, and even if the website crashes or malfunctions, the presentations are preserved.

## What is it good for?
As mentioned previously, this feature ensures that presentations are not lost even if our website crashes. The presentation, along with all associated files, is saved in a folder stored on the device and is therefore completely local.
This also allows you to work on multiple projects simultaneously. A separate subfolder is created within the main folder for each presentation, containing the presentation data. Visually reads this data, allowing you to easily create, delete, and switch between projects via the interface.

<img width="896" height="437" alt="image" src="https://github.com/user-attachments/assets/60ba7e76-1d3b-4653-8b6a-da5a19c07bb7" />


## The iOS Problem
As is so often the case, there are problems with iOS again. The system (iOS and iPadOS) doesn't allow pages in the browser to create, link to, and actively use a document/folder on the device. 
Since it wouldn't be effective or efficient to automatically download the entire presentation after every change, we opted for a different approach. For iOS devices, the data remains in their browser. 
We store the presentations in IndexedDB to make it more localized.
We're not entirely satisfied with this solution, but since we want to make the site as compatible as possible, we see this as a workable solution for now. 
We hope to get other options from Apple soon, but we don't expect it. But it works, so everything's fine.
