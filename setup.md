---
title: Setup
---
This lesson builds on the `AnalysisPayload` program developed in the ATALS GitLab lesson. To continue, you will need to have a working version of it.

If you had any issues working on your own project, you can always fork the example from the [usatlas-computing-bootcamp/v4-gitmodule-submodule-jetselector-simplecmake](https://gitlab.cern.ch/usatlas-computing-bootcamp/v4-gitmodule-submodule-jetselector-simplecmake) GitLab repository.

# Quick Start
Start your docker image with
~~~
docker run --rm -it -w /home/atlas/Bootcamp -v \
    $PWD:/home/atlas/Bootcamp atlas/analysisbase:21.2.85-centos7 \
    bash -c 'cp -r ssh-credentials ~/.ssh; cp gitconfig ~/.gitconfig ; bash'
~~~
{: .language-bash}


Clone the starting point using
~~~
git clone --recursive ssh://git@gitlab.cern.ch:7999/usatlas-computing-bootcamp/v4-gitmodule-submodule-jetselector-simplecmake.git
~~~
{: .language-bash}


{% include links.md %}
