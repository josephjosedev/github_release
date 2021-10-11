You can create a release to package software, along with release notes and links to binary files, for other people to use.


Releases are deployable software iterations you can package and make available for a wider audience to download and use.

Releases are based on Git tags, which mark a specific point in your repository's history. A tag date may be different than a release date since they can be created at different times. For more information about viewing your existing tags, see "Viewing your repository's releases and tags."

You can receive notifications when new releases are published in a repository without receiving notifications about other updates to the repository. For more information, see "Viewing your subscriptions."

Anyone with read access to a repository can view and compare releases, but only people with write permissions to a repository can manage releases. For more information, see "Managing releases in a repository."

You can manually create release notes while managing a release. Alternatively, you can automatically generate release notes from a default template, or customize your own release notes template. For more information, see "Automatically generated release notes."

People with admin permissions to a repository can choose whether Git Large File Storage (Git LFS) objects are included in the ZIP files and tarballs that GitHub creates for each release. For more information, see "Managing Git LFS objects in archives of your repository."

If a release fixes a security vulnerability, you should publish a security advisory in your repository. GitHub reviews each published security advisory and may use it to send Dependabot alerts to affected repositories. For more information, see "About GitHub Security Advisories."

You can view the Dependents tab of the dependency graph to see which repositories and packages depend on code in your repository, and may therefore be affected by a new release. For more information, see "About the dependency graph."

You can also use the Releases API to gather information, such as the number of times people download a release asset. For more information, see "Releases."




**Storage and bandwidth quotas**
<p>Each file included in a release must be under 2 GB. There is no limit on the total size of a release, nor bandwidth usage.</p>
