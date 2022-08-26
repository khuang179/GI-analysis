# GI-analysis
This is the CellProfiler pipeline for batch analysis of gall bladder size as stained using NBD-cholesterol.
Pipeline in brief as followed:
[   1] [Images]
  To begin creating your project, use the Images module to compile a list of files and/or folders that you want to analyze. You can also specify a set of rules to include only the desired files in your selected folders.

[   2] [Metadata]
  The Metadata module optionally allows you to extract information describing your images (i.e, metadata) which will be stored along with your measurements. This information can be contained in the file name and/or location, or in an external file.

[   3] [NamesAndTypes]
  The NamesAndTypes module allows you to assign a meaningful name to each image by which other modules will refer to it.

[   4] [Groups]
  The Groups module optionally allows you to split your list of images into image subsets (groups) which will be processed independently of each other. Examples of groupings include screening batches, microtiter plates, time-lapse movies, etc.

[   5] [Threshold]

[   6] [ConvertImageToObjects]

[   7] [SplitOrMergeObjects]

[   8] [MeasureObjectSizeShape]

[   9] [FilterObjects]

[  10] [MeasureObjectSizeShape]

[  11] [ExportToSpreadsheet]

[  12] [OverlayObjects]

[  13] [SaveImages]
