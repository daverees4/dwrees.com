---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Welcome
---

# I am a musician, software developer, improviser and escape room designer.  
I love playing the piano, composing and jamming with friends.  I still think music is the most amazing thing in the world and I want to spend as much of my time as possible around my favourite sounds. 

Technology has always fascinated me ever since I was very small.  It seemed like magic then, and seems even more like magic now.  I'm not a naturally talented developer, but learn to code enough to bring my ideas to life and build things I hope other people will find useful.  I'm less of a tech-utopianist than I was, but still think it's possible if we make the right calls, especially on AI and automation. 

When I was 31, I tried improv for the first time, after wanting to give it a go for years.  I loved it, and met some of the most brilliant and fun people I know.  I found a place where it's okay to fail, you're enough as you are and the point is to mess around making your friends laugh.  Now I'm very excited to be a part of this community that is growing all around the world. 

I adore puzzles. I think I inherited this from  my Mum.  We watched the Crystal Maze together and would delight (and despair) at the players' attempts to solve the games to win crystals.  During lockdown I made my own online escape room with a very talented artist friend.  Seeing the joy in someone's eyes when they figure out a puzzle I have created makes me very happy. 

I haven't followed a conventional path in life and am quite different in the things I value and think are important. Now I understand that I'm not wrong, just different.  

{% for now in site.nows limit:1 %}
# At the moment . . . 
{{now.content}}

last updated: {{ now.date | date: "%-d %B %Y" }}
{% endfor %}

