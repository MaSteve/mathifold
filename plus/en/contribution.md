---
layout: default
ident: contribution
lang: en
title: How to Contribute
---

<div style="position: relative;" align="center">
<p style="font-size: 40px;">How to Contribute</p>
</div>

<div class="plus">

	Willing to contribute? Here you'll find some instructions<br><br>

	<div>
        <div class="bcblue boxdissap">
        First steps
        </div>

        <div class="dissap" style="margin-left: 50px">

            <div>
                <div class="bcgreen boxdissap">
                Contact
                </div>

                <div class="dissap" style="margin-left: 50px">
                We'll be very happy to know that you like Mathifold! You may contact us at <code>mathifold@gmail.com</code>. We'll find the role in Mathifold that best suits you and you will know our team
                </div>
            </div>
            <div>
                <div class="bcgreen boxdissap">
                Fork in GitHub
                </div>

                <div class="dissap" style="margin-left: 50px">
                If you know GitHub, the easiest way to work with us is making your own copy (<code>fork</code>) of the resitory <a href="https://github.com/mathifold/mathifold" target="_blank">https://github.com/mathifold/mathifold</a> where you can build and send your contributions<br><br>

                If you're not used to GitHub, we encourage you to take the course on <a href="https://www.udacity.com/course/how-to-use-git-and-github--ud775" target="_blank">Git/GitHub at Udacity</a>. You'll love it!
                </div>
            </div>
            <div>
                <div class="bcgreen boxdissap">
                Other ways to contribute
                </div>

                <div class="dissap" style="margin-left: 50px">
                There are many other ways to contribute that do not involve directly code or programming: pedagogical advice, design, difussion... Any idea is welcome!
                </div>
            </div>
        </div>
    </div>

    <div>
        <div class="bcblue boxdissap">
        Keywords
        </div>

        <div class="dissap" style="margin-left: 50px">

            <div>
                <div class="bcgreen boxdissap">
                GitHub
                </div>

                <div class="dissap" style="margin-left: 50px">
                All the code that builds the webpage is located in the repository <b>mathifold/mathifold</b> at <code>GitHub</code>: <a href="https://github.com/mathifold/mathifold" target="_blank">https://github.com/mathifold/mathifold</a>. This way, everything is open-source. <code>GitHub</code> also provides a suitable platform to manage all the contributions
                </div>
            </div>
            <div>
                <div class="bcgreen boxdissap">
                jekyll
                </div>

                <div class="dissap" style="margin-left: 50px">
                Mathifold is built by the static site generator <a href="https://jekyllrb.com/" target="_blank"><code>jekyll</code></a>
                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                MathJax
                </div>

                <div class="dissap" style="margin-left: 50px">
                <a href="http://cdn.mathjax.org/" target="_blank"><code>MathJax</code></a> allows typesetting <code>LaTeX</code> formulas in the webpage
                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                SageMath
                </div>

                <div class="dissap" style="margin-left: 50px">
                <a href="https://www.sagemath.org/" target="_blank"><code>SageMath</code></a> provides a powerful lenguage for multiple mathematics applets
                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                Geogebra
                </div>

                <div class="dissap" style="margin-left: 50px">

                <a href="https://www.geogebra.org" target="_blank"><code>Geogebra</code></a> is being used for some applets, especially those involving plane and space geometry
                </div>
            </div>
            <div>
                <div class="bcgreen boxdissap">
                IPE Drawing Editor
                </div>

                <div class="dissap" style="margin-left: 50px">
                <a href="http://ipe.otfried.org/" target="_blank"><code>IPE Drawing Editor</code></a> is the software used for almost all the pictures
                </div>
            </div>
            <div>
                <div class="bcgreen boxdissap">
                Blender
                </div>

                <div class="dissap" style="margin-left: 50px">
                <a href="https://www.blender.org" target="_blank"><code>Blender</code></a> may be used for the rendering of mathematical animations
                </div>
            </div>

        </div>
    </div>

    <div>
        <div class="bcblue boxdissap">
        The creation of new posts
        </div>

        <div class="dissap" style="margin-left: 50px">

        The main task in building the webpage is the creation of new posts, the "little amounts of knowledge"

            <div>
                <div class="bcgreen boxdissap">
                Where are they located?
                </div>

                <div class="dissap" style="margin-left: 50px">
                Posts are <code>.md</code> files (<code>markdown</code>), and they must be located in the folder <code>_posts</code> inside its language subfolder, and its name must be formatted this way: <code>yyyy-mm-dd- ....... .md</code>. Inside each chapter, <code>jekyll</code> sorts the posts lexicographically, so ficticious dates may be needed
                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                Headers
                </div>

                <div class="dissap" style="margin-left: 50px">
                    Each post has a header, the post "data sheet", which has the following items

                    <ul>
                        <li><code>title</code>:  Title of the post</li>
                        <li><code>lang</code> and <code>category</code>: both the code of the language of the post</li>
                        <li><code>permalink</code>: <code>code-of-the-language/ident</code></li>
                        <li><code>ident</code>: an identifier that must be different for each post and that should synthesize its content. It usually starts with the type of the post</li>
                        <li><code>parent</code>: the identifier of the chapter to which the post belongs, according to <code>_data/nav.yml</code></li>
                        <li><code>kind</code>: the code of the kind of post</li>
                        <li><code>mathjax</code> and <code>sage</code>: <code>true</code> or <code>false</code> according to whether the page needs mathjax <code>mathjax</code> or <code>sage</code></li>
                        <li><code>geogebratube</code>: when embedding a Geogebratube applet, write down its identifying number</li>
                        <li><code>layout</code> and <code>type</code>: both should be left as <code>post</code></li>
                    </ul>
                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                Content
                </div>

                <div class="dissap" style="margin-left: 50px">
                The content is written in <code>markdown</code>, and may include <code>mathjax</code> or other extensions<br>

                One may include links to other posts with the command<br>

                {% raw %}

                <code>{% cite ident %}</code>

                {% endraw %}<br>

                and include pictures with the command <br>

                {% raw %}

                <code>{% resource name.ext %}</code>

                {% endraw %}<br>

                (see the section <code>_plugins</code> below for further information)

                </div>
            </div>

        </div>
    </div>

    <div>
        <div class="bcblue boxdissap">
        The files in the repository
        </div>

        <div class="dissap" style="margin-left: 50px">

        Each folder in the repository <code>mathifold/mathifold</code> has its own role in the construction of the webpage:

            <div>
                <div class="bcgreen boxdissap">
                <code>_data</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                This folder contains files with relevant data, usually as lists or dictionaries

                <ul>
                    <li>
                        <code>languages.yml</code>: Describes the list of languages currently supported in the webpage
                    </li>
                    <li>
                        <code>nav.yml</code>: Describes, by means of nested dictionaries, the first three levels in the tree structure of the webpage: <em>Topics</em>, <em>Subjects</em> and <em>Chapters</em>. Each item has an identifyer <code>ident</code>, one translation for each language in <code>languages.yml</code> and, for the two first levels, the subdictionary <code>children</code>
                    </li>
                </ul>

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>_includes</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                Each file in this folder has some fragment of code to be repeated in every page

                <ul>
                    <li>
                        <code>footer.html</code> contains the footer, which includes the informative buttons
                    </li>
                    <li>
                        <code>head.html</code> contains part of the <code>head</code> previous to <code>body</code>, where stylesheets and different scripts (<code>mathjax</code>, <code>sage</code>, <code>geogebra</code>, among others) are loaded
                    </li>
                    <li>
                        <code>header.html</code> has the header: links to upper levels to the left, searcher and language links to the right
                    </li>
                </ul>

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>_layouts</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                Each layout describes the content and design of each page. <code>default</code> is the standard content, which may be later specified to <code>home</code>, <code>topic</code>, <code>subject</code>, <code>chapter</code>, <code>post</code> and <code>search</code>.

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>_plugins</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                There are two kinds of implemented plugins, which may be called <em>generating</em> and <em>functional</em>

                <ul>
                    <li>
                        The generating plugins are <code>generate_home.rb</code>, <code>generate_topic.rb</code>, <code>generate_subject.rb</code> <code>generate_chapter.rb</code> and <code>generate_search.rb</code>, which generate pages according to <code>_data/nav.yml</code> (together with the search page), one for each language
                    </li>
                    <li>
                        The functional plugins are <code>cite.rb</code> and <code>resource.rb</code>, which implement different functions to be executed when writing a post. The implemented functions are<br><br>

                        {% raw %}

                        <code>{% cite ident %}</code>

                        {% endraw %}<br><br>

                        that links to the post having the matching <code>ident</code> (in the same language, if any) and <br><br>

                        {% raw %}

                        <code>{% resource name.ext %}</code>

                        {% endraw %}<br><br>

                        that looks for the picture <code>name.ext</code> inside the folder <code>/images/images</code>, places it and inserts a link to download the source if some file <code>name</code> (with different extension) is founded in the folder <code>/images/codes</code>

                    </li>
                </ul>

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>_posts</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                It contains the posts, whose structure was described earlier. They're divided in folders according to the language, but this divission is just towards translation logistics, since this ordering is meaningless for <code>jekyll</code>, that sorts all the posts in <code>_posts</code> by the information of their headers

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>_site</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                This is the directory where <code>jekyll</code> places the generated static webpage which is later uploaded to the server. This folder should not be modified directly

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>css</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                It contains the stylesheets. <code>custom.css</code> deals with the appearance of the webpage, while <code>subject_images.css</code>, <code>topic_images.css</code> and <code>symb.css</code> deal with the matching of pictures and should be implemented somehow to get a shorter code

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>images</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                We find inside the pictures of the entire webpage. The folders <code>topics</code>, <code>subjects</code>, <code>symb</code> and <code>others</code> contain the pictures outside the posts. The folders <code>images</code> and <code>codes</code> cointain the pictures to be used in the posts (preferrably in SVG format) together with their source codes, which are placed with the plugin <code>resource</code>

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>js</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                These are the script files. <code>lunr.min.js</code> and <code>search.js</code> implement the search of posts in <code>jekyll</code>-generated webpages according to <a href="http://jekyll.tips/jekyll-casts/jekyll-search-using-lunr-js/" target="_blank"><code>lunr.js</code></a>. <code>script.js</code> deals with the rest of script

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>plus</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                It has the files with the information of the bottom left buttons: <em>About</em>, <em>Reference Guide</em> and <em>How to Contribute</em> in several languages

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>templates</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                Several templates that include some scripts (<code>mathjax</code> and <code>sage</code>) to perform code trials without actually running <code>jekyll</code>

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                <code>xtras</code>
                </div>

                <div class="dissap" style="margin-left: 50px">
                Any other material somehow related to Mathifold which is wanted to be kept for future uses

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                other files
                </div>

                <div class="dissap" style="margin-left: 50px">
                Outside the previous folders one may find <code>_config.yml</code>, <code>404.md</code>, <code>app.yaml</code>, <code>favicon.ico</code>, <code>index.html</code>, <code>LICENSE.txt</code> and <code>README.md</code>

                </div>
            </div>

        </div>
    </div>

    <div>
        <div class="bcblue boxdissap">
        Tasks and Challenges
        </div>

        <div class="dissap" style="margin-left: 50px">

        Here you have a list of ideas devised in Mathifold for which enthusiast and experienced contributors are needed

            <div>
                <div class="bcgreen boxdissap">
                Accounts
                </div>

                <div class="dissap" style="margin-left: 50px">
                To create personal accounts, in which each user may customize its own mathematics study in Mathifold
                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                App
                </div>

                <div class="dissap" style="margin-left: 50px">
                Related to the webpage, to create an application (in <code>Android</code> and <code>iOS</code>) that allows and adapts the use of Mathifold in tablets and mobile devices, so that in the future any user may have in their device something like

                {% resource mathifold_app.png %}

                </div>
            </div>

            <div>
                <div class="bcgreen boxdissap">
                Translation
                </div>

                <div class="dissap" style="margin-left: 50px">

                To translate to every possible language, especially those more spoken, and starting with the more stable contents inside the webpage

                </div>
            </div>

        </div>
    </div>

</div>