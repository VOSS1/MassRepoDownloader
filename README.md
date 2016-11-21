# MassRepoDownloader
Sequential URL opener and downloader of available PDF's. 

As the name suggests, looking for a way to sequentially run through variations of a URL and download the PDF on each page automatically instead of individually opening each page and clicking download. 

Example: Program starts with https://repository/view/000001.pdf and downlaods the PDF
and then moves onto https://repository/view/000002.pdf 
all the way to https://repository/view/120000.pdf

There are however some pages that require you to click accept to the copyright policy so this will need to be accepted if it appears. 
Furthermore some variations of the number wont exist and if that error pops up it will need to move to the next variation in the sequence. 
