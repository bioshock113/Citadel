---
layout: default
title: August 28th, 2022
permalink: /journal/2022-08-28/
---

- [Home](/)
- [Journal Entries](/journal/)

# August 28th, 2022

---

#### Website Development

I've added sections for these journal entries and polished the CSS to handle the coloring of the headers and links.
I wasn't a fan of the original colors and had a hard time figuring out how to apply it correctly.
I kept getting build errors but eventually figured out I was overcomplicating it.

I may want to switch away from Markdown and use HTML in the future so I can have more control over presentation,
but I'm not sure if that is worth the cost of simplicity that Markdown gives me.

We'll see.

---

#### Home Server

I made a change with the operating system, and this **will** be the last time.
It's running *Windows Server 2019* so I can learn some Active Directory and make it into a domain controller.

Within Windows, I'm running an Ubuntu virtual machine in Hyper-V.
The purpose of this is to handle all of the Docker-related programs I want.

Now I could have simply installed executables for these programs and handled everything through Windows, but I wanted to run it inside Ubuntu without having Ubuntu running the whole machine.

I also learned how to add more storage to the Ubuntu VM.
I only needed a small amount of storage for the operating system, but since I plan on adding movies, TV shows, and music, I knew I would need more room.

So I used Hyper-V to create a 2 TB partition on my 3 TB HDD and added that to Ubuntu.
When I was attempting to do that last step, I broke my VM somehow and had to restart.

Luckily I had my process documented so it was easy to start over.

*Anyway*, I'm going to get the containers up and running for once. Here I go.
