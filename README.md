## Obtaining the Workspace:

1. Install the `repo` tool. Follow only the `Installing Repo` step: https://source.android.com/source/downloading#installing-repo
2. Create a directory where you will obtain the workspace:
```
mkdir -p bazel-playground && cd bazel-playground
```
3. Download the manifest file:
```
repo init -u https://github.com/lilianmoraru/bazel-playground-manifest.git
```
4. Now sync the workspace to obtain all the necessary tools and projects:
```
repo sync
```
<br/>

Now you can find all the projects under `projects` and all the tools under `tools`.