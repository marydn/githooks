# githooks

This is an example of Git Hooks implementation in a Symfony Project.

You can find the actual Git Hook script inside of [/.dotfiles/git/hooks/](.dotfiles/git/hooks)

In the [composer.json](composer.json) file, you will find a script named "check-git-config" that will be executed every time a 'composer install' or a 'composer update' command is executed. The script will set our hooks directory as the default git hooks path in the local project git configuration.

It's done using [Symfony Application console](https://symfony.com/doc/current/components/console.html#creating-a-console-application).