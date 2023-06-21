# hello-static

The simplest Hello World app that runs on Cloud Foundry using the Staticfile Buildpack.

**Usage:** `cf push static`

**Steps to regenerate the bare minimum:**
```
mkdir hello-static
cd hello-static
touch Staticfile
echo 'Hello World!' > index.html
```
