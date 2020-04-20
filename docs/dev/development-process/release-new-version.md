To release a new version:

1. Write up a changelog of all the changes made between the current version and the new version. You can run 
`git log --merges --grep 'Merge pull request' --pretty=format:%s [old-version]..head`
 to get every PR made between the previuous version and now
2. Update `VERSION` in `posthog/settings.py` AND `posthog-production/settings.py`
3. `git tag -a [version] -m "Version [version]"`
4. `git push origin head --tags`
