# GitKateStarted
This is a repo so that Kate can learn how Git works.

## why tho

Becuase Git works for more than just code, and because I think it's useful for non-developers—particularly those who work closely with developers or write about technology—to get a better understanding of how this aspect of software development works.

## so how

This repo contains the code for an extremely basic website that looks something like http://cosmocatalano.com/lab/gitscomplikated/. In fact, that site pulls the contents of the repo master branch from github every time it's loaded. 

The technology involved is super-basic in the interests of

- working everywhere
- minimimzing setup time
- displaying a single product that results from smaller interacting peieces
- not requiring the user to write any code.

After cloing the repo, you'll have a copy of the code that runs that website on your local machine. You can view that local version of the website by opening `index.html`, and you can edit the text of `index.html` by modifying files in the `text` directory. You can also add new files so long as they match the pattern `graf-`[a number]`.txt` (and so long as [a number] is less than 10).

## ok but

The idea is you could use this repo to create a branch, edit the files in the `text` folder to see how git recognizes changes and additions, and refresh `index.html` to see the impact of those local changes. You could also go through the process of commiting changes, publishing a branch to the remote, making a pull request to merge the branch back into the master, and see the changes live at http://cosmocatalano.com/lab/gitscomplikated/. 

If you really wanted to get freaky, you could have multiple people making simultaneous to `text` files, conflicting edits and see what happens when you try to merge…
