# Tabular Data I: Cleaning & Exploring
  
### OpenRefine Reference Material  
* Download the [Followup Tutorial for OpenRefine](https://github.com/cornell-colab/SGFDH-2020/blob/master/W3.%20Tabular%20Data:%20Clearning%20%2B%20Exploration/OpenRefineFollowUpTutorial.pdf) to understand the steps I took to start cleaning the Eastern State Penitentiary Data. (Use the "Download" button to get the PDF, or read straight from the browser.)
  
* [Official OpenRefine Documentation and Resources](https://openrefine.org/documentation.html)  
* [GREL Documentation](https://openrefine.org/documentation.html)  
* [GREL Recipes](https://github.com/OpenRefine/OpenRefine/wiki/Recipes)  
These "recipes" show you how to use GREL, sometimes combined with regular expressions, to accomplish common tasks. Can be very helpful!  
* [Clustering in Depth](https://github.com/OpenRefine/OpenRefine/wiki/Clustering-In-Depth)  
In case you want to understand the differences between various clustering methods.  
  
### OpenRefine Tutorials  
* [Getting started with OpenRefine](http://thomaspadilla.org/dataprep/) by Thomas Padilla  
A thorough introduction and reference geared toward humanists; the example data set is a list of books.  
* [Cleaning Data with OpenRefine](https://programminghistorian.org/en/lessons/cleaning-data-with-openrefine) by Seth van Hooland, Ruben Verborgh and Max De Wilde  
A detailed peer-reviewed tutorial published by *The Programming Historian*  
  
### Pivot Tables Reference Material
* [How to get data in the right format with pivot tables](https://blog.datawrapper.de/pivottables/) (A breezy conceptual introduction. Start here.)  
* [How to make Pivot Tables with Google Sheets](https://www.benlcollins.com/spreadsheets/pivot-tables-google-sheets/)   
* [How to make Pivot Tables with LibreOffice Calc](https://elearn.ellak.gr/mod/page/view.php?id=3015)  
* [How to make Pivot Tables with MicrosoftOffice Excel](https://support.microsoft.com/en-us/office/create-a-pivottable-to-analyze-worksheet-data-a9a84538-bfe9-40a9-a8e9-f99134456576?ui=en-us&rs=en-us&ad=us)  
  
Pivot tables summarize your dataset. Like OpenRefine, they are a tool for examining your data and getting to know it better, *as well as* to prepare your data for analysis through visualization or other methods. 

They’re especially useful for summarizing categorical data. Think of the columns in your metadata or data that contain text . There’s a good chance these are categorical data (e.g. *property, violence, sober, drinks heavily*). These words represent categories that your individual data items fall into.   

You can make pivot tables with any almost any spreadsheet software, including [LibreOffice Calc](https://www.libreoffice.org/) (free and open source), Google Sheets (free and proprietary), or MicrosoftOffice Excel (fee-based and proprietary; site licensed to the Cornell community).

As I mentioned in the OpenRefine guide, “open source” means that the code is open to inspection and modification by anyone. “Free” means users don’t pay fees to use it.( * ) If you don’t already have a firm favorite among these software options, I’d recommend making your first pivot table with **Sheets**, whose user interface I find the simplest. It's easy to jump in and start playing. But above, you can find step-by-step instructions for making pivot tables with any of these software packages. 

( * ) *Whether or not a company charges a fee to use their software, it may require users to pay with their privacy and their willingness to be subject to data surveillance, as in the case of both Google Sheets and MicrosoftOffice 365. LibreOffice does not collect data on users.*

  
  
### Before the Session

* **Download and Install** [OpenRefine 3.3](https://openrefine.org/download.html)  
Find detailed instructions for installation on this [OpenRefine Github page](https://github.com/OpenRefine/OpenRefine/wiki/Installation-Instructions).  
(Scroll down to the section with separate instructions for Windows and Macs.) Email Eliza with any problems or questions.

* **Download the dataset Eastern_State_Admission_Book.csv**  
-- Go to W3. Tabular Data: Cleaning + Exploration > Eastern_State_Admission_Book.csv, and click on the name of the dataset. A page will open, and you'll see a preview of the data table.  
-- Toward the upper-right, you'll see a button that says "Raw." RIGHT-click it and choose "Save Link As."  
-- Choose a place on your machine to store it, and download it. 

* **Sign up for an account** on [Datawrapper](https://datawrapper.de).

* **Sign up for an account** on [Cornell's Carto instance](https://cornell.carto.com/signup).

* **Read** Drucker, J. (2011) [Humanities Approaches to Graphical Display](http://www.digitalhumanities.org//dhq/vol/5/1/000091/000091.html). *Digital Humanities Quarterly* 5(1).
This article will be very relevant to both the Wednesday and Thursday sessions, and you don't need to read it all at once. Feel free to start it today and finish tomorrow, if your time is limited. 

* **Read** Davis, H. (2019). "[A Dataset is a Worldview](https://towardsdatascience.com/a-dataset-is-a-worldview-5328216dd44d)," a blog post on *Towards Data Science*, a *Medium* vertical.  
This short post is about datasets used in machine learning, which is why I originally had planned to assign it later in the summer. But the idea that a dataset reflects a worldview is just as relevant to your creation of metadata schema as it is to considering the data used in machine learning, and it should be good food for thought now as well as later.

#### Further Reading for Future Reference: Datasets that Encode and Reinforce Racism  

Agwin, J. and Colleagues. (2016). [Machine Bias: risk assessments in criminal sentencing](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing). *ProPublica*.  

Eubanks, V. (2018). [Automating Inequality: how high-tech tools profile, police, and punish the poor](https://newcatalog.library.cornell.edu/catalog/10228118). New York: St. Martin's Press.  
  
Noble, S. (2018). [Algorithms of Opression: how search engines reinforce racism](https://newcatalog.library.cornell.edu/catalog/10294895). New York: NYU Press.


### During the Session  

The dataset we'll use today is dervied from an admission book of prisoners in the Eastern State Penitentiary in the early 19th century in eastern Pennsylvania. I created it by combining these two separate datasets:    
[Eastern State Penitentiary Admission Book A](https://repository.upenn.edu/mead/22/)  
[Eastern State Penitentiary Admission Book B](https://repository.upenn.edu/mead/21/)  
Both published by Scott Ziegler, Michelle Zioglas, and students. Accessed via the Magazine of Early American Datasets.

[Boxnote of questions about the data](https://cornell.app.box.com/notes/677010855433)

### After the Session  
* Play around a little more with Open refine. Try to address (or partially address) some of the research questions in the [boxnote](https://cornell.app.box.com/notes/677010855433), or use it with your own data. 

Questions to consider in your reflection post:  
* What new questions, insights, or confusions did you generate during or after today's session?
* In what ways does your project dataset reflect a worldview of your own, someone else's, or multiple other people's?
* What are some ways you may want to clean your current project dataset? How confident are you feeling about devising a strategy to do so? What else do you want to learn?  
