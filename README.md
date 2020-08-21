# landing-page-boilerplate

A pure client-side landing page template that you can freely fork, customize, host and link to your own domain name (e.g. using Github Pages).
Relies on Mailchimp (for user email subscriptions) and Google Analytics (for stats).

# Features

- Static HTML page => no fancy hosting needed (Github Pages does it for free)
- Light source code => fast to load
- Responsive design
- User emails are submitted to the Mailchimp list of your choice, so you can contact them when needed.

# How to use

- Fork this project to your own Github account;
- Change the name, description and link, on the page of your freshly forked project on Github;
- Make sure it's published, by opening `<your_github_username>.github.io/<your_fork_name>`;
- Update the following lines in index.html:
  - enter the title of your page/product into the `<title>` and `<h1>` elements;
  - update the baseline of your page/product into the first `<p>` element;
  - update the content of all the `<meta>` elements;
  - update the `action` attribute of the `<form>` element, so that it leads to your own [Mailchimp](http://mailchimp.com) list;
  - update the `UA-1858235-15` code with your own Google Analytics code;
  - replace `favicon.ico` with your own; ([ICO Converter](http://www.icoconverter.com/) can help)
- Replace the [default background image](https://www.pexels.com/photo/dawn-landscape-mountains-nature-1852/) with your own in `/res/background.jpg`;
- If you want to use Github Pages as hosting platform and that your custom domain name links to it, set your custom domain name in the `CNAME` file; (read more [here](https://help.github.com/articles/setting-up-a-custom-domain-with-github-pages/))
- Go to your subdomain, hard-refresh a few times (or wait 24 hours), to make sure that it works;
- Submit your own email in the subscription form to make sure that it works;
- Go to your Google Analytics dashboard to make sure that your page view was taken into account;
- Enjoy your free landing page! :-)
