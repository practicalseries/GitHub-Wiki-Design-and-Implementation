<a name="idtop"></a><!-- 🟢TOP OF PAGE - MARKER  (BLANK LINE BELOW)   -->

<img width="896px" src="./ps-github-wiki-logo.svg" alt="PAL Logo showing Wiki Documentation heading"><!-- 🟢TOP OF PAGE - LOGO IMAGE -->
<p align="right"><img height="18" src="https://img.shields.io/badge/Web_ID-1700--ecm-blue"></p>      <!-- 🟢TOP OF PAGE - WEB ID     --> 

# 17<!--        🟥H1🟥--><img width="088" height="1" src="https://psop.uk/wi-s" alt="Spacer">Managing a Wiki

This section covers various points about managing and maintaining a Wiki. This is from the point of view of using a text editor on local machine to modify the Wiki. 

In particular, using Visual Studio Code (<a href="https://code.visualstudio.com/">VS Code</a>) as the text editor for the Wiki and then using the facilities of VS Code to push any modifications to GitHub.

This section covers the following:

<table name="l-17-01" align="center">   <!-- LIST START🔽🔽(BLANK LINE ABOVE) -->
<!-- LIST ROW 01  --><tr><td valign="top">&#x2776;<!-- 1  --></td>
    <td><!-- TEXT -->Revision control and managing commits (what to worry about and what not to worry about)</td></tr>
<!-- LIST ROW 02  --><tr><td valign="top">&#x2777;<!-- 2  --></td>
    <td><!-- TEXT -->Using the Wiki history to find the first commit point (needed for point 3 below)</td></tr>
<!-- LIST ROW 03  --><tr><td valign="top">&#x2778;<!-- 3  --></td>
    <td><!-- TEXT -->Rebasing a Wiki to remove all the intermediate commit points</td></tr>
<!-- LIST ROW 04  --><tr><td valign="top">&#x2779;<!-- 4  --></td>
    <td><!-- TEXT -->Search engine response to Wiki contents</td></tr>
<!-- CAPTION -->          <tr><th width="52"></th><!-- SPACER -->
<!-- LIST WIDTH -->         <th align="left" width="798"><sup>
<!-- CAPTION TEXT --><!-- TEXT -->List 17.1 &mdash; Managing a Wiki contents
                           </sup></th></tr>
</table>                              <!-- LIST END    🔼🔼(BLANK LINE BELOW) -->

This section is largely based on what I have come to understand by developing Wikis for the PracticalSeries of publications. None of it is essential, but some of it may be useful to you.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->


## 17.1<!--     🟥H2🟥--><img width="081" height="1" src="https://psop.uk/wi-s" alt="Spacer">Revision control

*Here we go then.*

A Wiki is a *(restricted)* repository in its own right (see <a href="01-introducing-the-github-wiki#14the-wiki-is-its-own-repository">section&nbsp;1.4</a>). It is restricted because GitHub doesn’t give all the facilities available to a normal repository to a Wiki, you cannot, for example, have branches within a Wiki repository (GitHub just ignores them and only works with the Master branch).

Now, when you clone a repository to a local machine (see <a href="02-cloning-a-wiki">section&nbsp;2</a>) and open it in some Git friendly text editor (<a href="https://code.visualstudio.com/">VS Code</a> for example) you get the full facilities available for managing any repository and you can apply them all to the Wiki &mdash; you can, for example,  create branches within the Wiki and push them back to GitHub, only to have GitHub ignore them completely.

So, while you have all the facilities to manage the Wiki as a full-blown repository, it is best to scale down your ambitions and just use those facilities that GitHub wants you to 

*So here’s my guide:*

Don’t think of the Wiki as a development environment where you can create branches, assign them to different development teams and merge everything back together at some later date.

<p align="center"> ${\huge \color{#C00000}\text{Think\ of\ a\ Wiki\ as\ a\ document\ that\ only\ one\ person\ can\ work\ on\ at\ a\ time.}}$ </p>

**Each time the document is changed and reposted to GitHub, the document revision is updated.**

Obviously, more than one person can clone the Wiki and each person can modify bits of it as they like, but there is no structure (like branches) that allows for different development paths or group working. Essentially, you would have to incorporate everybody else’s changes into your cloned copy before pushing your own changes back to GitHub. *It’s a bit of a nightmare.*

The best mechanism for managing a Wiki that I’ve come up with, is to have a single person controlling the Wiki, let’s call them the *“Lead”* (in my case, it is me). 

That person sets up the underlying folder structure and pushes the result to GitHub.

If someone else wants to work on the Wiki, the Lead sets up a new folder in the structure and assigns it to that person, that person can work in that folder (add, delete, change files &c.), but only in that folder (no other part of the Wiki). 

This process is repeated for each person working on the Wiki, the each get their own folder.

When an individual changes a file in their folder and wants to push it to GitHub to test it, they must first pull any other changes made to the Wiki to their local machine. Since all these changes will have been made in other folders (allocated to other people), there will be no impact on the local modified files. The whole lot can then be pushed back to GitHub.

Where common files or files in directories outside an individual’s development folder, these must be managed by the Lead.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 17.1.1<!--  🟥H3🟥--><img width="074" height="1" src="https://psop.uk/wi-s" alt="Spacer">Managing commits

When I first started writing a Wiki, I was meticulous about commit messages *(as I am with a proper repository)*, it rapidly dawned on me that this was a pointless exercise.

This is a screen shot of part of my modification history for this Wiki:

<table name="f-17-01" align="center"><!-- FIGURE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Figure row --> <tr><td>
<!-- LINK -->         <a href="./17-0000/02-images/figm-17-01.png" title="Use ctrl+click to open image in new tab">
<!-- FIGURE -->         <img width="850" src="./17-0000/02-images/figm-17-01.png" alt="Wiki development revisions">
                    </a></td></tr>
<!-- CAPTION -->    <tr><th align="center"><sup>
<!-- CAPTION TEXT -->   Figure 17.1 &mdash; Wiki development revisions
                    </sup></th></tr>
</table>                             <!-- FIGURE END  🔼🔼(BLANK LINE BELOW) -->

There are pages of it. At the time of writing I’d made 2,229 commits to the Wiki and they all had the same commit message:

&emsp;&emsp;&emsp;🚧 Wiki construction — initial development

While you are developing a Wiki, there is absolutely no point in trying to record changes or manage the revisions in anyway. Think how many changes you make to a Word document, spelling mistakes, changing an image, updating the contents and links, not to mention incorporating comments from other people.

There are thousands of changes and not much point in trying to explain each one, at best you enter commit message such as: *“typographical corrections”, “incorporated comments from MG”* &c. Such commit messages do not impart much information. 

The only useful information for previous commits is the date of the commit. Along the lines of: *“I’m pretty sure that section was OK last Tuesday, let’s load that one and see what I screwed up in the meantime”*.

It’s different once the Wiki is complete, reviewed and published. At that point, changes will be fewer and probably associated with a revision of a particular section &c. Under these circumstances more meaningful commits may be a practical option.

**Until then don’t worry about commit messages.**

In VS Code, with Source Control active, there is a list of the most recent commits in the left-pane. If you right-click one of these messages you can copy the commit message and just paste it into the commit box at the top and then commit the changes. It's an easy way to re-use the same commit message.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 17.2<!--     🟥H2🟥--><img width="077" height="1" src="https://psop.uk/wi-s" alt="Spacer">Finding the first Wiki commit

GitHub can display the history of any Wiki page (this was discussed in <a href="01-introducing-the-github-wiki#141viewing-a-wiki-page-history">section&nbsp;1.4.1</a>). Broadly, go to the Wiki page you want to see the history of and click the revisions link (this is in the title area of the page, just below the title text).

This is the current history for the Home page of this repository:

<table name="f-17-02" align="center"><!-- FIGURE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Figure row --> <tr><td>
<!-- LINK -->         <a href="./17-0000/02-images/figm-17-02.png" title="Use ctrl+click to open image in new tab">
<!-- FIGURE -->         <img width="850" src="./17-0000/02-images/figm-17-02.png" alt="Wiki page revision">
                    </a></td></tr>
<!-- CAPTION -->    <tr><th align="center"><sup>
<!-- CAPTION TEXT -->   Figure 17.2 &mdash; Wiki page revision
                    </sup></th></tr>
</table>                             <!-- FIGURE END  🔼🔼(BLANK LINE BELOW) -->


As was said in <a href="01-introducing-the-github-wiki#141viewing-a-wiki-page-history">section&nbsp;1.4.1</a>, this history isn’t particularly useful, for a start you cannot see the complete history for the whole Wiki, just a page at a time.

The only practical use for the GitHub Wiki history is for finding the first commit number for the Wiki. This is only needed if you rebase the Wiki to get rid of all the commits that accrue in the creation process (this is discussed in detail in the next section).

To find the first commit for the repository, go to the Home page of the Wiki and click the revisions link at the top-left of the page to open the history page (shown above).

Scroll to the bottom of the page and keep clicking Older until you get to the oldest commit:

<table name="f-17-03" align="center"><!-- FIGURE START🔽🔽(BLANK LINE ABOVE) -->
<!-- Figure row --> <tr><td>
<!-- LINK -->         <a href="./17-0000/02-images/figm-17-03.png" title="Use ctrl+click to open image in new tab">
<!-- FIGURE -->         <img width="850" src="./17-0000/02-images/figm-17-03.png" alt="Wiki first commit">
                    </a></td></tr>
<!-- CAPTION -->    <tr><th align="center"><sup>
<!-- CAPTION TEXT -->   Figure 17.3 &mdash; Wiki first commit
                    </sup></th></tr>
</table>                             <!-- FIGURE END  🔼🔼(BLANK LINE BELOW) -->

The first commit for this Wiki is `dd06e43`. 

This is the easiest way to find the first commit number for the Wiki (the home page is the first page to be created when starting the Wiki).

*You may be wondering why it important to know the first commit point?*

The answer is: *it isn’t*, not unless you want to purge all the commits that have been made (apart from the first one) and reload the current state of the pages back in as the second commit point (I.e. to essentially reset the repository and remove all the many commits that have been made in the meantime).

I discuss this process in the next section.

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

## 17.3<!--     🟥H2🟥--><img width="077" height="1" src="https://psop.uk/wi-s" alt="Spacer">Rebasing the Wiki

**Rebasing scares the shit out of most people, no one really understands it and if you get it wrong you can lose all your stuff.**

I have a golden rule about rebase: ${\huge \color{#C00000}\text{Never\ use\ rebase.}}$ 

*So why do I want to use it?*

*Well*, what I’m describing here breaks most of the rules about version control and repositories, but it can be used to tidy up all those unwanted commits in a Wiki.

Let’s say you find yourself in the position that I’m in: I’ve finished the Wiki and I want to publish it to GitHub, but I’ve got 2000+ commits from developing, testing, correcting &c. and I don’t want any of them. Essentially, what I want is for the finished version to be the first (or more practically, the second) commit.

In short, I don’t want all the intervening commits for every spelling correction and minor document tweak that was made. I want to go from the initial commit (when the Wiki was created) to the finished article.


 ${\huge \color{#C00000}\text{Yep,\ it\ breaks\ the\ basic\ rule\ of\ a\ version\ control\ system.}}$

My thought process was this: I’m never going to wade through 2000 commit point looking for a particular change, so what’s the point in having them. Surely it is better to get rid of all those commits and start with the finished article. I can then monitor the commits from there on, these being more relevant, smaller in scope and more traceable.

***That said, this process is brutal and is not for the faint hearted. I would practice it on a development Wiki that you don’t care about first.***

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 17.3.1<!--  🟥H3🟥--><img width="072" height="1" src="https://psop.uk/wi-s" alt="Spacer">Summarising the rebase process 

To summarise, the process does the following *(I've included this so you know what will happen before you actually do it for real)*:


<table name="l-17-02" align="center">   <!-- LIST START🔽🔽(BLANK LINE ABOVE) -->
<!-- LIST ROW 01  --><tr><td valign="top">&#x2776;<!-- 1  --></td>
    <td><!-- TEXT -->Back up the full Wiki repository, everything, the whole folder including the <code>.git</code> directory. *This is so I can put everything back when I inevitably screw things up*</td></tr>
<!-- LIST ROW 02  --><tr><td valign="top">&#x2777;<!-- 2  --></td>
    <td><!-- TEXT -->Rebase the Wiki repository back to the very first commit. This deletes everything in the repository <em>(all the work you have done, all the intervening commits, everything &mdash; all gone)</em></td></tr>
<!-- LIST ROW 03  --><tr><td valign="top" height="61">&#x2778;<!-- 3  --></td>
    <td valign="top"><!-- TEXT -->${\huge \color{#C00000}\text{It’s\ at\ this\ point\ you\ start\ panicking.\ Never\ fear,\ hold\ your\ nerve}}$</td></tr>
<!-- LIST ROW 04  --><tr><td valign="top">&#x2779;<!-- 4  --></td>
    <td><!-- TEXT -->From the backup (step 1), copy everything <strong>except</strong> the <code>.git</code> directory and paste it into the (now empty) Wiki folder <em>(if you were to copy the .git directory you would just put the re-pository back to where it was)</em></td></tr>
<!-- LIST ROW 05  --><tr><td valign="top">&#x277A;<!-- 5  --></td>
    <td><!-- TEXT -->VS Code will now be showing a whole load of files that need to be staged and committed (every file in the final version of the Wiki will now be showing as added or modified). Enter an appropriate commit message, stage and commit everything</td></tr>
<!-- LIST ROW 06  --><tr><td valign="top">&#x277B;<!-- 6  --></td>
    <td><!-- TEXT -->Forcibly push the changes from VS Code to GitHub <em>(this overwrites everything in the GitHub Wiki without asking questions)</em></td></tr>
<!-- LIST ROW 07  --><tr><td valign="top">&#x277C;<!-- 7  --></td>
    <td><!-- TEXT -->The Wiki now has two commits, the first when it was initially created in GitHub and the second, the finished article</td></tr>
<!-- CAPTION -->          <tr><th width="52"></th><!-- SPACER -->
<!-- LIST WIDTH -->         <th align="left" width="798"><sup>
<!-- CAPTION TEXT --><!-- TEXT -->List 17.2 &mdash; Summarising the rebase process
                           </sup></th></tr>
</table>                              <!-- LIST END    🔼🔼(BLANK LINE BELOW) -->

That’s the theory, this is how you do it:

**[:arrow_up: Top](#idtop)**<!-- END OF SECTION - LINK TO TOP🔽🔽(BLANK LINE ABOVE) -->
<HR>                        <!-- END OF SECTION - SEPARATING LINE                    -->
<br>                        <!-- END OF SECTION - PADDING    🔼🔼(BLANK LINE BELOW) -->

### 17.3.2<!--  🟥H3🟥--><img width="068" height="1" src="https://psop.uk/wi-s" alt="Spacer">Executing the rebase process

This is the step-by-step guide (with pictures).

<table name="l-17-03" align="center">   <!-- LIST START🔽🔽(BLANK LINE ABOVE) -->
<!-- LIST ROW 01  --><tr><td valign="top">&#x2460;<!-- 1  --></td>
    <td><!-- TEXT -->Commit any outstanding changes to the Wiki repository and synchronise everything with GitHub</td></tr>
<!-- LIST ROW 02  --><tr><td valign="top">&#x2461;<!-- 2  --></td>
    <td><!-- TEXT -->Identify the very first commit point for the Wiki using the mechanism given in <a href="#172finding-the-first-wiki-commit">section&nbsp;17.2</a>.
In my case the commit point is: <code>dd06e43</code>
</td></tr>
<!-- LIST ROW 03  --><tr><td valign="top">&#x2462;<!-- 3  --></td>
    <td><!-- TEXT -->Using Windows File Explorer navigate to the Wiki folder, in my case it looks like this:<br><br>
<a href="./17-0000/02-images/figm-17-03a.png" title="Use ctrl+click to open image in new tab"><img src="./17-0000/02-images/figm-17-03a.png" alt="Git directory"></a><br><br>
Make sure that the folder has a <code>.git</code> directory within it (highlighted)    
    </td></tr>
<!-- LIST ROW 04  --><tr><td valign="top">&#x2463;<!-- 4  --></td>
    <td><!-- TEXT -->Copy the folder (in my case the <code>GitHub-Wiki-Design-and-Implementation.wiki</code> folder) and paste it into some other location — I.e. make a backup of the whole Wiki repository
Make sure the backup has the <code>.git</code> directory within it
</td></tr>
<!-- LIST ROW 05  --><tr><td valign="top">&#x2464;<!-- 5  --></td>
    <td><!-- TEXT -->In VS Code, select ${\color{#00B050}\langle\text{Terminal}\rangle}$ and then ${\color{#00B050}\langle\text{New\ Terminal}\rangle}$ to open the Git terminal Window at the bottom:<br><br>
<a href="./17-0000/02-images/figm-17-03b.png" title="Use ctrl+click to open image in new tab"><img src="./17-0000/02-images/figm-17-03b.png" alt="Git directory"></a>   
    </td></tr>
<!-- LIST ROW 06  --><tr><td valign="top">&#x2465;<!-- 6  --></td>
    <td><!-- TEXT -->The terminal window looks like this:<br><br>
<a href="./17-0000/02-images/figm-17-03c.png" title="Use ctrl+click to open image in new tab"><img src="./17-0000/02-images/figm-17-03c.png" alt="Git directory"></a>
</td></tr>
<!-- LIST ROW 07  --><tr><td valign="top">&#x2466;<!-- 7  --></td>
    <td><!-- TEXT -->

Enter the command:<br>
    
${\large \color{#0050C0}\text{git\ reset\ --hard\ }\color{#C00000}\text{[commitNo]}}$    
    
 Where ${\large \color{#C00000}\text{[commitNo]}}$ is the first commit point number, in my case it is   
    
${\large \color{#0050C0}\text{git\ reset\ --hard\ dd06e43}}$<br><br>
<a href="./17-0000/02-images/figm-17-03d.png" title="Use ctrl+click to open image in new tab"><img src="./17-0000/02-images/figm-17-03d.png" alt="Git directory"></a>
</td></tr>
<!-- LIST ROW 08  --><tr><td valign="top">&#x2467;<!-- 8  --></td>
    <td><!-- TEXT -->The repository now only has the single Home.md file within it (everything else has gone)<br><br>
<a href="./17-0000/02-images/figm-17-03e.png" title="Use ctrl+click to open image in new tab"><img src="./17-0000/02-images/figm-17-03e.png" alt="Git directory"></a></td></tr>
<!-- LIST ROW 09  --><tr><td valign="top">&#x2468;<!-- 9  --></td>
    <td><!-- TEXT -->Now go to the backup created in step &#x2463; and select everything apart from the <code>.git</code> directory<br><br>
<a href="./17-0000/02-images/figm-17-03f.png" title="Use ctrl+click to open image in new tab"><img src="./17-0000/02-images/figm-17-03f.png" alt="Git directory"></a>
</td></tr>
<!-- LIST ROW 10  --><tr><td valign="top">&#x2469;<!-- 10 --></td>
    <td><!-- TEXT -->Copy the selection <strong>(everything but the <code>.git</code> directory)</strong> from the backup.<br><br>    
Navigate to the proper repository and paste it in (replacing the <code>Home.md</code> file in the process)</td></tr>
<!-- LIST ROW 11  --><tr><td valign="top">&#x246A;<!-- 11 --></td>
    <td><!-- TEXT -->VS Code will now show a large number of new files (533 changes in my case):<br><br>
<a href="./17-0000/02-images/figm-17-03g.png" title="Use ctrl+click to open image in new tab"><img src="./17-0000/02-images/figm-17-03g.png" alt="Git directory"></a>
</td></tr>
<!-- LIST ROW 12  --><tr><td valign="top">&#x246B;<!-- 12 --></td>
    <td><!-- TEXT -->Stage all the files, enter a commit message and commit the changes:<br><br>
<a href="./17-0000/02-images/figm-17-03h.png" title="Use ctrl+click to open image in new tab"><img src="./17-0000/02-images/figm-17-03h.png" alt="Git directory"></a><br><br>

${\large \color{#C00000}\text{DO\ NOT\ SYNC\ THE\ REPOSITORY\ IF\ PROMPTED\ TO\ DO\ SO}}$
</td></tr>
<!-- LIST ROW 13  --><tr><td valign="top">&#x246C;<!-- 13 --></td>
    <td><!-- TEXT -->At this stage, the Wiki on the GitHub site is still as it was, it has a full history of all the commits made. If we were to sync the local repository and GitHub, everything would just be copied back from GitHub and everything would be as it was</td></tr>
<!-- LIST ROW 14  --><tr><td valign="top">&#x246D;<!-- 14 --></td>
    <td><!-- TEXT -->
    
The local repository currently just has two commits (the original one, and the one we have just made by adding all the files back in).

To make those changes permanent, the local Wiki must be pushed to GitHub overwriting what is there. This requires a forced push (i.e. it pushes the changes to GitHub without pulling any existing changes first).

In the terminal, enter the command:

${\large \color{#0050C0}\text{git\ push\ origin\ HEAD\ --force}}$<br><br>
<a href="./17-0000/02-images/figm-17-03i.png" title="Use ctrl+click to open image in new tab"><img src="./17-0000/02-images/figm-17-03i.png" alt="Git directory"></a>   
</td></tr>
<!-- LIST ROW 15  --><tr><td valign="top">&#x246E;<!-- 15 --></td>
    <td><!-- TEXT -->After a short period, it comes back with a response, this was mine:<br><br>
<a href="./17-0000/02-images/figm-17-03j.png" title="Use ctrl+click to open image in new tab"><img src="./17-0000/02-images/figm-17-03j.png" alt="Git directory"></a>
</td></tr>
<!-- LIST ROW 16  --><tr><td valign="top">&#x246F;<!-- 16 --></td>
    <td><!-- TEXT -->Looking at the history, the Wiki now has (in my case):<br><br>
<a href="./17-0000/02-images/figm-17-03k.png" title="Use ctrl+click to open image in new tab"><img src="./17-0000/02-images/figm-17-03k.png" alt="Git directory"></a><br><br>

There are just two commits, the original commit (when the Wiki was created) and now the second commit with all the files back where they should be. 

I.e. all the intervening commits are gone and the Wiki is back in the same state as it was at the final commit before all this started
</td></tr>
<!-- CAPTION -->          <tr><th width="52"></th><!-- SPACER -->
<!-- LIST WIDTH -->         <th align="left" width=844"><sup>
<!-- CAPTION TEXT --><!-- TEXT -->List 17.3 &mdash; Executing the rebase process
                           </sup></th></tr>
</table>                              <!-- LIST END    🔼🔼(BLANK LINE BELOW) -->

***Not nerve wracking at all.***

## 17.4<!--     🟥H2🟥--><img width="076" height="1" src="https://psop.uk/wi-s" alt="Spacer">Wikis and search engine visibility

This is a confusing topic and I’m not clear what the situation is. 

Currently, search engines are allowed to craw GitHub Wiki files, at least they are not excluded in the GitHub.com `robots.txt` file:

<table name="t-cc-01" align="center"><!-- TABLE START🔽🔽(BLANK LINE ABOVE) -->
<!-- HEADER ROW --> <tr>
                        <th colspan="2"">GitHub: robots.txt file</th>
                    </tr>
<!-- DATA ROW -->   <tr>
                        <td width="400" align="left" valign="top">

```txt
# If you would like to crawl GitHub contact us 
# via https://support.github.com?tags=dotcom-robots
# We also provide an extensive API: 
# https://docs.github.com
User-agent: baidu
crawl-delay: 1


User-agent: *

Disallow: /*/*/pulse
Disallow: /*/*/projects
Disallow: /*/*/forks
Disallow: /*/*/issues/new
Disallow: /*/*/issues/search
Disallow: /*/*/commits/
Disallow: /*/*/branches
Disallow: /*/*/contributors
Disallow: /*/*/tags
Disallow: /*/*/stargazers
Disallow: /*/*/watchers
Disallow: /*/*/network
Disallow: /*/*/graphs
Disallow: /*/*/compare

Disallow: /*/tree/
Disallow: /gist/
Disallow: /*/download
Disallow: /*/revisions
Disallow: /*/commits/*?author
Disallow: /*/commits/*?path
Disallow: /*/comments
Disallow: /*/archive/
Disallow: /*/blame/
Disallow: /*/raw/
```
</td>
                        <td width="400" align="left" valign="top">

```txt
Disallow: /*/cache/
Disallow: /.git/
Disallow: */.git/
Disallow: /*.git$
Disallow: /search/advanced
Disallow: /search$
Disallow: /*q=
Disallow: /*.atom$
Disallow: /ekansa/Open-Context-Data
Disallow: /ekansa/opencontext-*
Disallow: */tarball/
Disallow: */zipball/

Disallow: /*source=*
Disallow: /*ref_cta=*
Disallow: /*plan=*
Disallow: /*return_to=*
Disallow: /*ref_loc=*
Disallow: /*setup_organization=*
Disallow: /*source_repo=*
Disallow: /*ref_page=*
Disallow: /*source=*
Disallow: /*referrer=*
Disallow: /*report=*
Disallow: /*author=*
Disallow: /*since=*
Disallow: /*until=*
Disallow: /*commits?author=*
Disallow: /*report-abuse?report=*
Disallow: /*tab=*
Allow: /*?tab=achievements&achievement=*

Disallow: /account-login
Disallow: /Explodingstuff/
```
</td>
                    </tr>
<!-- CAPTION -->    <tr><th colspan="2" align="left"><sup>
<!-- CAPTION TEXT -->Table 17.1 &mdash; GitHub robots.txt file
                     </sup></th></tr>
</table>                             <!-- TABLE END  🔼🔼(BLANK LINE BELOW) -->

That said, the GitHub documentations (<a href="https://docs.github.com/en/communities/documenting-your-project-with-wikis/about-wikis">here</a>) says the following:

“Search engines will only index wikis with 500 or more stars that you configure to prevent public editing.”
I don’t have 500 stars, so I can’t tell if this is true

*“Search engines will only index wikis with 500 or more stars that you configure to prevent public editing.”*

I don’t have 500 stars, so I can’t tell if this is true

I’ve also noted that when I’ve searched for things in the process of writing this, GitHub Wikis tend not to come up in the search results.

Either way, if your Wiki is configured for public editing (see <a href="01-introducing-the-github-wiki#f-01-03">here</a>) it won’t feature in 

To turn this off, click ${\large \color{#00B050}\langle\text{Settings}\rangle}$ for the repository, select ${\large \color{#00B050}\langle\text{General}\rangle}$ in the left-hand menu bar and then in the Features area (main section) tick the ${\large \color{#00B050}\langle\text{Restrict\ editing...}\rangle}$ box:


GitHub Wikis are definitely searchable from the GitHub search box.

<br><br>            <!-- END OF PAGE - 🟥🟥🟥🟥🟥 PADDING🔽🔽(NO BLANK LINE ABOVE) -->
<hr>                <!-- END OF PAGE - 🟥🟥🟥🟥🟥 SEPARATING LINE                   -->
<a name="idend"></a><!-- END OF PAGE – 🟥🟥🟥🟥🟥 MARKER 🔼🔼                      -->