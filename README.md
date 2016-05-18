# ISMIR 2016 Late-Breaking/Demo Submission

Thanks for your interest in submitting a late breaking/demo (LBD) paper for ISMIR 2016.
The submission guidelines for this year are as follows:

- A submission should be an extended abstract describing a preliminary result, idea, application, or a demo of a new product or technology.
- Submissions should have one page (preferred) or two pages (maximum) of content, with no limit on the size of the bibliography (i.e. all pages past the second must only contain references).
- All LBD papers are required to be presented by one of the authors as a poster (and optionally a live demo) on the final day (August 11th) of ISMIR 2016.
- This year, the LBD session will be open to the public, so we particularly encourage submission of projects of interest to a broad/nonscientific audience.
- Submission will be open until August 10th, 2016.  Please note that if you are submitting something which is _very late_-breaking, you will still be expected to present it as a poster during the LBD session.
- Submissions should not be anonymized.
- All submissions will undergo a light peer review.  Note that all submissions and review will all be completely viewable by the public.
- Templates are available for [LaTeX](https://raw.githubusercontent.com/ismir-net/ismir2016-lbd/master/templates/ISMIR2016-LBD_tex_template.zip) and [Word](https://raw.githubusercontent.com/ismir-net/ismir2016-lbd/master/templates/ISMIR2016-LBD_word_template.zip).

This year, we are handling submissions through GitHub!
If you don't have experience with git/GitHub, don't worry, you can do everything from your browser; see below for a tutorial.
If you are comfortable with using git, please follow these steps to create a submission:

1. Fork this repository.
2. In your fork, add a PDF of your paper to the submissions folder.  The PDF should be named `(first author's last name)-(first word of title).pdf`; for example, if the first author is Joe Shmoe, and the paper's title is "Music is Cool", the PDF should be called `shmoe-music.pdf`.
3. [Create a pull request](https://github.com/ismir-net/ismir2016-lbd/pull/new/master) to merge your fork.  Make the title of the pull request the title of the paper.
4. Review will take place within the pull request; after any necessary revisions the paper will be accepted when the pull request is merged.

## Submission Tutorial

Fortunately, GitHub is easy to use even if you have no experience with git or the command line.
The following steps will create a new submission; if you have any issues, please don't hesitate to email [craffel@gmail.com](craffel@gmail.com).

1. Download the [LaTeX](https://raw.githubusercontent.com/ismir-net/ismir2016-lbd/master/templates/ISMIR2016-LBD_tex_template.zip) or [Word](https://raw.githubusercontent.com/ismir-net/ismir2016-lbd/master/templates/ISMIR2016-LBD_word_template.zip) template and write your LBD extended abstract.
1. If you're using Word, save the Word document as a PDF.  If you're using LaTeX, you should have a PDF already.
1. Rename your PDF `(first author's last name)-(first word of title).pdf`; for example, if the first author is Joe Shmoe, and the paper's title is "Music is Cool", the PDF should be called `shmoe-music.pdf`.
1. If you aren't signed up for GitHub, sign up [here](http://github.com/join).  You don't need a paid account.
1. Create a fork of this repository by clicking on the "Fork" button at the top of this page, which looks like this:

   ![fork](https://raw.githubusercontent.com/ismir-net/ismir2016-lbd/master/images/fork.png "Fork")
1. In your new repository, navigate to the `submissions` directory (after navigating, the URL should be something like https://github.com/your-github-username/ismir2016-lbd/tree/master/submissions):

   ![submissions](https://raw.githubusercontent.com/ismir-net/ismir2016-lbd/master/images/submissions.png "submissions")
1. Click the "Upload files" button:

   ![upload](https://raw.githubusercontent.com/ismir-net/ismir2016-lbd/master/images/upload.png "Upload")
1. Upload your correctly-named PDF, and hit "Commit changes" at the bottom of the page:

   ![commit-changes](https://raw.githubusercontent.com/ismir-net/ismir2016-lbd/master/images/commit-changes.png "Commit changes")
1. Click the "New Pull Request" button:

   ![new-pull-request](https://raw.githubusercontent.com/ismir-net/ismir2016-lbd/master/images/new-pull-request.png "New pull request")
1. You should see a page which looks like this; click the "Create Pull Request" button:

   ![create-pull-request](https://raw.githubusercontent.com/ismir-net/ismir2016-lbd/master/images/create-pull-request.png "Create pull request")
1. Make the pull request title the title of your paper, and click the "Create Pull Request" button:

   ![title-create-pull-request](https://raw.githubusercontent.com/ismir-net/ismir2016-lbd/master/images/title-create-pull-request.png "Title/create pull request")
1. This will take you the pull request page for your paper, with a URL like https://github.com/ismir-net/ismir2016-lbd/pull/2.  Save this URL for future reference.  At this point, you have submitted your extended abstract; don't close the pull request.
1. The paper will be reviewed within the pull request.  You may be instructed to update your PDF with a few changes.  To do so, simply follow steps 6-8 again with your updated PDF (i.e. navigate to the `submissions` directory in your fork and upload your new updated PDF).  The pull request will be updated automatically.
1. Your pull request will be merged (i.e. your PDF will be included in the main repository) once the review is over.  That's it!

If you have any questions or problems, feel free to email craffel@gmail.com.
