# lab02-debugging

# Collaborators 
Jimin Choi (No collaborators, I was out sick during the demo). <br/>
**Shadertoy Link:** https://www.shadertoy.com/view/wfjBRm

# My Process
1. First bug was the vec2 bug on line 97, which was more obvious than the other bugs. There is no "vec" type.
2. Passing in the wrong vec2 for the raycast function. I had to read through the code multiple times to notice that uv2 was never being used.
3. Specular reflection passing in eye instead of dir. 

# Setup 

Create a [Shadertoy account](https://www.shadertoy.com/). Either fork this shadertoy, or create a new shadertoy and copy the code from the [Debugging Puzzle](https://www.shadertoy.com/view/flGfRc).

Let's practice debugging! We have a broken shader. It should produce output that looks like this:
[Unbelievably beautiful shader](https://user-images.githubusercontent.com/1758825/200729570-8e10a37a-345d-4aff-8eff-6baf54a32a40.webm)

It don't do that. Correct THREE of the FIVE bugs that are messing up the output. You are STRONGLY ENCOURAGED to work with a partner and pair program to force you to talk about your debugging thought process out loud.

Extra credit if you can find all FIVE bugs.

# Submission
- Create a pull request to this repository
- In the README, include the names of both your team members
- In the README, create a link to your shader toy solution with the bugs corrected
- In the README, describe each bug you found and include a sentence about HOW you found it.
- Make sure all three of your shadertoys are set to UNLISTED or PUBLIC (so we can see them!)
