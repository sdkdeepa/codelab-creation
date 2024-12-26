authors: Deepa 
summary: Creating engaging codelabs
id: codelab-tutorial-1
categories: Sample
tags: codelab, go, node, claat
status: Published 

# How to Write a Codelab
<!-- ------------------------ -->
## Installation 
Duration: 10

### What you will need? 
1. [Install GO](https://go.dev/dl/)
    ![Image](assets/1.png)
2. Set path in `zshrc` or `bash_profile`
    ```bash 
    export GOPATH=$HOME/go
    export GOROOT=/usr/local/go
    export PATH=$PATH:$HOME/go/bin
    ```
    **Also, check if `go` is installed by running `go version`**
3. Install node 20 
    `npm install 20`
4. Codelab as a tool(clat) - 
        `go install github.com/googlecodelabs/tools/claat@latest`
5. Create`codelabs`folder alsong with the following it
        `mkdir codelabs/instructions.md`
        `mkdir/assets/image1.png`

    ![Image2](assets/2.png)

### Creating engaging code labs
We will see how to how to write codelabs with the following:

- Adding a Summary 
- Set the duration of each step
- How to include code snippets, hyperlink, images and formatting the content. 
- Finally, how to covert it to a codelab!


<!-- ------------------------ -->
## Adding Summary

At the top of your mark down add the following like this:

```
authors: Deepa 
summary: How to Write a Codelab
id: codelab-tutorial-1
tags: codelab, go, node, claat
status: Published 

# How to Write a Codelab
<!-- ------------------------ -->
## Installation 
Duration: 1

### What you will need? 
1. Install GO  - https://go.dev/dl/
    ![Image](assets/1.png)
2. Set path in `zshrc` or `bash_profile`
    ```bash 
    export GOPATH=$HOME/go
    export GOROOT=/usr/local/go
    export PATH=$PATH:$HOME/go/bin
    ```
3. Install node 20 
    `npm install 20`
4. Codelab as a tool(claat) - 
        `go install github.com/googlecodelabs/tools/claat@latest`
5. Need a text editor to open `codelabs` folder
        `mkdir codelabs/instructions.md`
         `mkdir/assets/image1.png`
![Image2](assets/2.png)

### Creating engaging code labs
We will see how to how to write codelabs with the following:

- Set the durtation of each step
- How to include code snippets, hyperlink items, include images and formatting. 
- Finally, how to covert it to a codelab!

<!-- ------------------------ -->

## Title - Step 2
Duration: 15
### Heading 3
 **This is a Text**
<!-- ------------------------ -->
## Title - Step 3
Duration: 10
### Content

<!-- ------------------------ -->

```


<!-- ------------------------ -->
## Engaging  your audience
Duration: 1
### By Hyperlinking Content
[Youtube - GDG Channel](https://www.youtube.com/@GoogleDeveloperGroups)

### Adding Images  and  gifs
![Puppy](assets/puppy.jpg)

![gif](assets/AppDemo.gif)

### YouTube Video Embeds 

Use a video tag like so `< video id="DWAinkJ54AP8" > < /video >` to embed a video uploaded to YouTube with the URL https://www.youtube.com/watch?v=DWAinkJ54AP8

### Formating

Checkout the official documentation here: [Codelab Formatting Guide](https://github.com/googlecodelabs/tools/blob/master/FORMAT-GUIDE.md)

<!-- ------------------------ -->
## Coverting Markdown to HTML
Duration: 5

Once you are done adding the content to `instructions.md`, all you need to do is run the following command on your terminal. (Make sure you are in the right path)

`claat export /path to/codelabs/instructions.md`

![Folder Creation](assets/5.png)

A `codelab-tutorial-1` folder will be created. This is the id that we gave in the **Summary section**. If you open the `index.html` in your browser, you will be able to see this locally.

![codelab-tutorial-1](assets/3.png). 

You can now host your codelab to any hosting application.
![FinalImage](assets/4.png)

## Thank you!
🎉🎉 Congratulations! Now you are set for you next workshop!

See how you can use this new skill in creating an enaging content. For all of it and more, see you next time 👋🏼👋🏼!
![Happy Holidays and a Wonderful New Year 2025](assets/wishes.png)


