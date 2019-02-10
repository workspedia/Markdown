Markdown is commonly used in different websites, text editors, and applications, so most of the
time we don't need to install a specific converter to use it because it is integrated into the tool
that we are already using. 

However, in order to directly transform any Markdown document,
we can use a Markdown converter.
In 5 easy steps, we can install Markdown and get it set up on your system.

Step 1 – Prerequisites
The official Markdown converter is a script written in Perl. This is the converter that we are going to use.
Before we use Markdown, we will need to check that we have all of the required elements listed here:
  Perl 5.6.0 or later
  The Markdown script
Step 2 – Downloading and installing Perl
Step 3 – Verifying that Perl is working
Step 4 – Downloading Markdown
Step 5 – Running Markdown
in our command-line interface, we run Perl that takes two arguments: 
the path of the Markdown script that we just downloaded and the path of the Markdown file that we want convert.
perl Markdown.pl markdown-file.md
Markdown will process the Markdown file; 
the resulting output after running the script is the HTML code shown in the terminal.
To save this output, we redirect the standard output to an HTML file:
perl Markdown.pl markdown-file.md > output-file.html

