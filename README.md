# Description

You will create a link.tree like web page, it will be a single web page that will contain all the links to your social media / contact / places of interest.

From link.tree
> You get one link to house all the content you’re driving followers to. Share that link anywhere, like your Instagram bio, Facebook posts or Twitch profile.
> Send followers anywhere: articles, webstore, events, socials and more.

# Requirements

So obviously for this project you will need:

- multiple destination where you want to send your followers, it might include: LinkedIn profile, Facebook profile, Instagram profile(s), personal blog, web store, etc.

- develop it in flask

- read the content dynamically via a yaml file (links.yaml)


- generate the buttons with the correct href to *redirect*



# links.yaml

```yaml
# point to your own profile pic you want to display in your link.my.bio
picture: "static/filename_of_your_selfie.[png|jpg]"
# short auto biography about yourself
shortbio: "brief paragraph that contains your short bio"

# links will be an array of any amount of links you want your followers to discover
links:
    - facebook:
        enable: True
        link: "https://url_to_your.facebook.profile"
        description: "check my facebook"
    - instagram:
        enable: True
        link: "https://url_to_your.instagram.profile"
        description: "How Cool my photos are in instagram :camera:"
    - blog:
        enable: False
        link: "lorem ipsum"
        description: "lorem ipsum dorem"
    - etc:
        enable: False
        link: "http://etc.etc"
        description: "any other link you want your followers to see"

```



# Example