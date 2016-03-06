## Getting Started

### Dependancies

In order to index content gsl is required, ensure it is installed via:

```
brew install gsl
```

### Starting the Server

Make sure your gems are up to date:

```
bundle install
```

Start the development server using the following command:

```
bundle exec foreman start
```

This will take some time to start in order to build an index for related posts.

### Updating Jekyll source files

After making changes to the development files on the `source` branch, add, commit and push them as normal

### Publishing changes

In order to publish the resulting changes to the site, you will need to update the `master` branch which is checked out into the `_site` directory of your working copy while the development process is running.
