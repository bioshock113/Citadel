
- [Home](/index.md)
- [Journal Entries](/journal.md)


# August 28th, 2022

---

#### Website Development

I've added sections for these journal entries and polished up some of the CSS to handle the coloring of the headers and links. I wasn't a fan of the original colors and I had a heck of a time figuring out how to apply it correctly. I kept getting build errors but eventually I figured out I was just overcomplicating it. Story of my life. Anyway now they're working and I'm happy.

I do think I may want to switch away from Markdown and use HTML in the future so I can have more control over exactly how things are presented but I'm not sure if thats worth the cost of simplicity that Markdown affords me.

We'll see.

---

#### Home Server

So I made a change with the operating system and this **will** be the last time.
It's running *Windows Server 2019* so I can learn some active directory stuff and make it into a domain controller. (Still don't know **exactly** what that is but I have a good idea.)

Within Windows I'm then running an Ubuntu virtual machine within Hyper-V. The purpose of this is to handle all of the docker related programs I want.

Now I could have simply installed the executables of these docker programs I want and handle it all through Windows but...I don't know. Maybe I'm a masochist but I wanted to do it within Ubuntu without having to have Ubuntu running the whole machine.

I also learned how to add more storage to the Ubuntu VM. I only needed a small amount of storage for the actual OS, but since I plan on adding movies/tv shows/music, I knew I'd need more room.

So I used Hyper-V to create a 2TB partition on my 3TB HDD and added that to Ubuntu. 

When I was attempting to do that last step I actually broke my VM somehow and had to restart.

Lukcily I had my process documented so it was easy to restart.

*Anyway*, I'm gonna get the containers up and running for once. Here I go!

---

