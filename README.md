# FlutterCamp 

FlutterCamp provides resources and content to support developers who want to learn more about [Flutter](https://flutter.io) in self-guided or group-study learning contexts.

The initial focus of this repo is to create and share a series of short presentations (with accompanying code) to explore various topics in Flutter, in byte-sized segments. The repository will have the following branches:
 
  * _master_ containing intro deck (slides) and code samples (directories)
  * _template_ containing a _GitPitch_ hosted talk template
  * various branches (from _template_) each focused on a subtopic


## About GitPitch

[GitPitch](https://gitpitch.com/) is a presentation service that can convert Git-accessible _Markdown_ files into a GitPitch-hosted presentation. It is inspired by [reveal.js](https://revealjs.com/#/) but is easier to use for the following reasons:

 * Markdown syntax is easier to learn (no JS knowledge)
 * Conversion to hosted presentation is effortless (automatic)
 * Templates & HTML/CSS knowledge can enable richer features

I've created the base "template" for #FlutterCamp talks in the _template_ branch, using a GitPitch template. Simply create new named branches from this one for each sub-topic. The resulting presenation will be automatically available at _https://gitpitch.com/<github-username>/<github-reponame>/<branch-name>_.

The master branch **PITCHME.md** will serve as a _Table of Contents_ for quick navigation to the GitPitch decks associated with various branches.

