Sublime Comments
===============================================

Easy comments for Sublime Text 3, based on [Idiomatic CSS](https://github.com/necolas/idiomatic-css).


## Install

First use Package Control to add this repo as a package (remember to remove .git from the end of the repo’s URL) and then install package. 

1. cmd + shift + p -> Add as Repo
2. cmd + shift + p -> Install package 
3. sublime-comments

And you’re done!


## Usage

There are several shortcuts for the different comment blocks.

### Basic Comment

	/* This is a basic comment */

Enter the shortcut `c` followed by the `tab` key.

### Section Comment

	// ==========================================================================
   	// This is a Section Comment
    // ========================================================================== 

Enter the shortcut `c1` followed by the `tab` key.

### Sub-Section Comment

    // This is a Sub-Section Comment
    // ----------------------------------------------------------------------


Enter the shortcut `c2` followed by the `tab` key.

### Long Comment

	/**
	 * Short description using Doxygen-style comment format
	 *
	 * The first sentence of the long description starts here and continues on this
	 * line for a while finally concluding here at the end of this paragraph.
	 *
	 * The long description is ideal for more detailed explanations and
	 * documentation. It can include example HTML, URLs, or any other information
	 * that is deemed necessary or useful.
	 *
	 * @tag This is a tag named 'tag'
	 *
	 * TODO: This is a todo statement that describes an atomic task to be completed
	 *   at a later date. It wraps after 80 characters and following lines are
	 *   indented by 2 spaces.
	 */


Enter the shortcut `cl` followed by the `tab` key

### Todo List Comment

	/**
	 * TODO:
	 *
	 * => Write some code
	 * => Make some lists
	 *
	 */

#### Todo List Comment Usage

Enter the shortcut `ct` followed by the `tab` key
