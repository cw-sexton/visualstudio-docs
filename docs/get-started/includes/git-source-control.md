---
ms.date: 08/11/2021
ms.technology: vs-ide-general
ms.custom: vs-get-started
ms.author: tglee
author: TerryGLee
manager: jmartens
ms.topic: include
---
::: moniker range=">=vs-2019"

## Add Git source control

Now that you've created your app, you might want to add it to a Git repository. We've got you covered; Visual Studio makes that process easy with Git tools you can use directly from the IDE.

> [!TIP]
> Git is the most widely used modern version control system, so whether you're a professional developer or if you're learning how to code, Git can be very useful to you. If you are new to Git, the [https://git-scm.com/](https://git-scm.com/) website is a good place to start. There, you’ll find cheat sheets, a popular online book, and Git Basics videos.

To associate your code with Git, you start by creating a new Git repository where your code is located. Here's how.

1. In the status bar at the bottom-right corner of Visual Studio, select the **Add to Source Control** button, and then select **Git**.

    :::image type="content" source="../media/vs-2022/git-add-source-control.png" alt-text="Screenshot of the Git source control buttons below the Solution Explorer pane, with the Add to Source Control button highlighted.":::

1. In the **Create a Git repository** dialog box, sign in to GitHub.

    :::image type="content" source="../media/vs-2022/git-create-repo.png" alt-text="Screenshot of the Create a Git Repository dialog window where you can sign in to GitHub.":::

    The repository name is auto-populated based on your folder location. By default, your new repository is private, which means you're the only one who can access it.

    > [!TIP]
    > Whether your repository is public or private, it's best to have a remote backup of your code stored securely on GitHub even if you aren't working with a team. This also makes your code available to you no matter what computer you're using.

1. Select **Create and Push**.

    After you've created your repository, you'll see status details in the status bar.

    :::image type="content" source="../media/vs-2022/git-new-private-repo-status-details.png" alt-text="Screenshot of the repo status bar that's below the Solution Explorer pane in Visual Studio.":::

    The first icon with the arrows shows how many outgoing/incoming commits are in your current branch. You can use this icon to pull any incoming commits or push any outgoing commits. You can also chose to view these commits first, too. To do so, click the icon, and then select **View Outgoing/Incoming**.

    The second icon with the pencil shows the number of uncommitted changes to your code. You can click this icon to view those changes in the **Git Changes** window.

To learn more about how to use Git with your app, see the [Visual Studio version control documentation](../../version-control/index.yml) page.

::: moniker-end