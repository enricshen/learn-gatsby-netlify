---
path: third
date: 2022-09-01T03:55:53.173Z
title: THis is my third blog
---
dsfasdfsdaf

asdfsad

fasd

fsad

fs

df

sadfsd

<!--StartFragment-->

1.  only invited users to access your CMS, but if you're just experimenting, you can leave it open for convenience.
2. If you'd like to allow one-click login with services like Google and GitHub, check the boxes next to the services you'd like to use, under **External providers**.
3. Scroll down to **Services > Git Gateway**, and click **Enable Git Gateway**. This authenticates with your Git host and generates an API access token. In this case, we're leaving the **Roles** field blank, which means any logged in user may access the CMS. For information on changing this, check the [Netlify Identity documentation](https://www.netlify.com/docs/identity/).

## [](https://www.netlifycms.org/docs/gatsby/#start-publishing)Start publishing

It's time to create your first blog post. Login to your site's `/admin/` page and create a new post by clicking New Blog. Add a title, a date and some text. When you click Publish, a new commit will be created in your GitHub repo with this format `Create Blog “year-month-date-title”`.

Then Netlify will detect that there was a commit in your repo, and will

<!--EndFragment-->