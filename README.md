# Fungal vs bacteroal keratitis clasification

Initially, the data consisted of two folders, each containing several subfolders of images of fungal keratitis in the fungal folder or bacterial keratitis in bacterial folder.

In the first step, I gathered all images of subfolders in relative root folder; all photos in the bacterial subfolder were collected into a single folder named bacterial, and I did this with a function in utils folder.

Next, I added a suffix to the name of every image in the root folders; for example, the suffix _bacterial was appended to the end of any image in bacterial folder and similarly for pictures of the fungal folder. 

Finally, all images were moved to a single folder named bct_fng. This folder was the main folder we were dealing with throughout the modeling process. The labeling was based on the suffix of each image, if the image name ended in _bacterial, the image would be labeled bacterial, and so on.
