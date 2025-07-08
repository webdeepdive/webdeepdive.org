# Contribute to webdeepdive.org and Get Your Own Custom Path\!

Do you want to have your own custom URL shortener under the `webdeepdive.org` domain? By contributing to our `paths.json` file on GitHub, you can create your own short paths that redirect to your desired destinations.

-----

## How It Works

The `webdeepdive.org` website uses a simple JSON file called `paths.json` to manage all of its URL redirects. This file, located at `https://github.com/webdeepdive/webdeepdive.org/blob/main/paths.json`, contains a list of key-value pairs. The "key" is the custom path you want to create, and the "value" is the destination URL it will redirect to.

For example, if you add the following to `paths.json`:

```json
{
  "my-awesome-link": "https://www.your-website.com/your-page"
}
```

Then, anyone who visits `https://webdeepdive.org/my-awesome-link` will be redirected to `https://www.your-website.com/your-page`.

-----

## How to Contribute

To add your own custom path, you'll need to contribute to our open-source project on GitHub. Here's a step-by-step guide:

### 1\. Fork the Repository

First, you'll need to create your own copy (a "fork") of the `webdeepdive.org` repository.

  * Go to our GitHub page: [https://github.com/webdeepdive/webdeepdive.org](https://www.google.com/search?q=https://github.com/webdeepdive/webdeepdive.org)
  * Click the "**Fork**" button in the top-right corner. This will create a copy of the repository under your own GitHub account.

### 2\. Edit the `paths.json` File

Now that you have your own fork, you can edit the `paths.json` file.

1.  In your forked repository, navigate to the `paths.json` file.

2.  Click the pencil icon (✏️) to edit the file directly on GitHub.

3.  Add a new line with your desired path and destination. **Important:** Make sure your new entry is added within the existing curly braces `{}` and that you add a comma `,` after the preceding entry if yours is not the last one. Follow the JSON format, with your path as the key and your destination URL as the value, both enclosed in double quotes.

    ```json
    {
      "existing-path": "https://example.com",
      "your-new-path": "https://your-destination-url.com"
    }
    ```

4.  Once you've added your path, scroll to the bottom of the page and "Commit changes". Provide a brief, clear message describing what you've added (e.g., "Add path for my-awesome-link").

### 3\. Create a Pull Request

After you've committed your changes to your fork, the final step is to request that we pull your changes into the main project. This is done through a "Pull Request."

1.  Go back to the main repository page: [https://github.com/webdeepdive/webdeepdive.org](https://www.google.com/search?q=https://github.com/webdeepdive/webdeepdive.org).
2.  You should see a message saying "Your recently pushed branches..." with a button to "**Compare & pull request**". Click it.
3.  If you don't see that message, click on the "**Pull requests**" tab and then click the "**New pull request**" button.
4.  Ensure the base repository is `webdeepdive/webdeepdive.org` and the head repository is your fork.
5.  Review your changes one last time and click the "**Create pull request**" button.

Once you've submitted your pull request, our team will review your contribution. If everything looks good, we'll merge it, and your custom path will be live on `webdeepdive.org`\!

-----

We're excited to see the amazing paths you create. Happy contributing\!
