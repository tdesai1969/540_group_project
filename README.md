# 540_group_project
Group_7_Attrition

# Installing dependencies

We will be using conda to build our environments.

The packages and versions are defined in env.yml. The command to install the environment will be:

```
conda env create -f env.yml
```

This will create an environment called DSC540.

Additional dependencies can be added. If conda does not have the package, then we can use pip to install it. Simply add the package name and version in the yaml entry for pip.


# Best practices

- Ensure that you are always working in your folder.
- Add comments to improve readability. Expect that others will be looking at your notebooks.
- Split different parts of the project into different notebooks. Have a different notebook for each thing you do. The idea is to not have long and cluttered notebooks. Keep it as simple as possible.
- Try to add markdown to the notebooks. That can help readability and is good for adding explanations and notes that are too long for comments. It also helps to add structure to the notebooks.
- Always use the same versions of the libraries as the group. This is especially important when dealing with numpy and any packages with numpy as a dependency.
- You may add additional libraries for any reason. Just make sure to add it to the environment yaml file. If it is a conda package, then list it in conda. If it is a pip package, list it under pip. This way we are all guaranteed to have the environment created in the same way.

