Do not push any code to that repository.

# How to publish
1. On https://github.com/nextcloud, tag appropriate commit on the source repository
2. Push the new tag to this repository
3. Create release on this repository

# Automatic package and publish
1. Make sure you have the [necessary workflow](https://github.com/nextcloud/.github/blob/master/workflow-templates/appstore-build-publish.yml) on your https://github.com/nextcloud source repository
2. Make sure your tagged commit also have the workflow
3. Make sure this repository have the proper `APP_PRIVATE_KEY` secret set
4. Make the `nextcloud_release_service` user is a co-maintainer of your app on https://apps.nextcloud.com/
5. Make sure you have admin rights to this repository
