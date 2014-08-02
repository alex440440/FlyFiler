FlyFiler
========

FlyFilter is an Excel Macro which lets you to filter the data while you are typing.

FlyFilter: filter while typing	 	 	 	 	 	 	 	 
 	 	to  filter on the fly	Ctrl + T	
 	 	to save the filtering	Enter	
 	 	to cancel the filtering	Esc	
 	 	Notes:

* If you have multiple header rows - turn on filtering on the row you want to be filtered

* If you don't have filtering enabled, the search is on all the used range of the spreadsheet.

If you do have filtering enabled - the search is on the filtered region.

Your filter settings are saved.

* Cells highlighting- there are two options for now:

a. Not highlight the cells containing the text you search for. This is the default option.

b. Highlight the cells containing the text you search for.

Use this option with caution - in this case your filtered range background colors will be defaulted to transparent after you press Esc. So if your cells colors are important to you - use the first option. If you still determined to use cells highlighting - use Ctrl+G.

* If you have filtering enabled only on partial columns of the used range, the macro will use an empty utility column after the filtered range. If there is no empty column after the filtered range in the original table, it will be inserted by the macro. Your original data will not be affected - it will shift 1 column right. The column is used for the inner magic of the algorithm. If you press Esc, the utiliy column will be removed and your table will get to the original state, and if you press Enter to save the filtering state, the column will stay.