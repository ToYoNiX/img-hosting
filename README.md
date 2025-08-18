# What is this repo for?

There is a raw button in github that will give you the raw file to open it in your browser or curl it directly from a repo. This allows you to call the raw content directly from github which means that it acts like a cloud storage. But this feature is not available for images or videos, but there is a work around you can do to host images and videos here on github and use the urls in like emails or even html pages that you send to somebody instead of sending the image or video along side the other things. Which is a game changer in some scenarios.

# Why?!

Why to even bother with Github for that when you have other services that is specialized in this thing? Well, these services often are restrictive on the image quality and size. While github still has size limitations, it's a lot larger than these sites and doesn't do any image processing while uploading the image. So the file you upload will be the exact file you get with the url.

# Something to keep in mind

In github, There is a file size limit for each file. By default it is 100mb. and you can use [Git LFS](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-git-large-file-storage) for that and it will increase that limit depending on your plan. And if your repo reached 5gb, you may get an email from github support querying what exactly you’re doing that is taking up so much space. So keep that in mind.

# Tutorial

- Create a public repo exactly like this one.
- Upload your images and videos to it via upload or whatever.
- That't it. You can use your files following this format
    - `https://raw.githubusercontent.com/yourusername/repository/main/images/image.png`

# Test

You can test that by taking this html code as an example for that
```html
<img src="https://raw.githubusercontent.com/ToYoNiX/img-hosting/main/CA.png">
```