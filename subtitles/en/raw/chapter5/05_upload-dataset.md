In this video we'll take a look at how you upload your very own dataset to the Hub. The first you'll need to do is create a new dataset repository on the Hub. Just click on your profile icon and select the "New Dataset" button. Next we need to assign an owner of the dataset. By default, this will be your Hub account, but you can also create datasets under any organisation that you belong to. Then we just need to give the dataset a name and specify whether it is a public or private dataset. Public datasets can be accessed by anyone, while private datasets can only be accessed by you or members of your organisation. And with that we can go ahead and create the dataset! Now that you have an empty dataset repository on the Hub, the next thing to do is add some data to it! You can do this with Git, but the easiest way is by selecting "Upload file" and uploading the files directly from your machine. After you've uploaded the files, you'll see them appear in the repository under the "Files and versions" tab. The last step is to create a dataset card. Well documented datasets are more likely to be useful to others (including your future self!) as they provide the context to decide whether the dataset is relevant or whether there are any biases or risks associated with using the dataset. On the Hugging Face Hub, this information is stored in each repository’s README.md file and there are two main steps you should take. First you need to create some metadata that will allow your dataset to be easily found by others on the Hub. You can create this metadata using the Datasets Tagging Application which we'll link to in the video description. Once you have created the metadata, you can fill out the rest of the dataset card and we provide a template that is also linked in the video. And once your dataset is up on the Hub, you can load it using the trusty load_dataset() function! Just provide the name of your repository and a data_files argument for the files and you're good to go!