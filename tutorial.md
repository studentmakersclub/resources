# Tutorial: Using SMC

This is a tutorial of how to use Student Makers Club.


## Getting Started

Message to SMC Bot ([@makersclubbot](http://telegram.me/makersclubbot)) with `/login` command. You will get the login URL. Open it in browser.

![](https://i.imgur.com/QX5GlvN.png)

Then join the chat at [@makersclub](https://t.me/makersclub).


## Posting updates

Use the `/update` command in DM or server channel to post updates.

```
/update <your activity> #projectTag
/update <your activity> #skillTag
```

![](https://i.imgur.com/wqSK6Yr.png)


## Setting skills

Use the `/skill` command.

```
/skill [skill-handle] [score from 1 to 5]
```

Example

```
/skill js 3
/skill react 2
```

The skill score reflects your expertise in the skill. This value will be used later to track your progress as well as to collaborate better. The number associated with the skill roughly translates as follows.

```js
export const skillMap = {
	1: 'novice',
	2: 'competent',
	3: 'proficient',
	4: 'expert',
	5: 'master'
}
```

Skills are a work in progress. Please help by adding more skills to [skills.py](data/skills.py) file.


## TIPS

* Set up a [public username](https://telegram.org/faq#q-what-are-usernames-how-do-i-get-one) for your Telegram profile for best experience.
* Don't shy away from making updates in the group.
