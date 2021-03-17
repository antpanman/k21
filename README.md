# k21
## Lab 1 - Explore Service Portal 
### Exercise 1 - Access the default Service Portal
1. Enter service portal in the navigator
2. Click the Service Portal Home link to open the Service Portal in a new tab/window
You should see something that looks like below
(screenshot 1)
### Exercise 2 - Execute the "match all" query
1. Enter `***` in the search box and hit the ENTER key
The character sequence `***` is special syntax which matches all documents that are searchable for a specific portal (and accessible by the current user). 
It is a quick way to test if AI Search is enabled and there are documents in the index.
Because there is no search term, no relevancy scores are calculated, so the search executes quickly. No hit highlighting is applied to the resiults.
You should see something that looks like below
(screenshot 2)
### Exercise 3 - Execute a keyword search
1. Enter `iphone` in the search box and the ENTER key
You should see something that looks like below
(screenshot 3)
Notice how the word `iphone` is highlighted? This is hit highliighting of the matched terms which gives a user some indication why the result was returned.
### Exercise 4 - Utilize the Navigation Tabs
1. Click on the **Knowledge** tab
These tabs are known as *Navigation Tabs* and they allow a user to display results from one source at a time. In this case, we are restricting results to just Knowledge Base articles.
You should see something that looks like below
(screenshot 4)
2. Click on the **All** tab to return to displaying all results in order of relevance
### Exercise 5 - Filter results
1. Click to expand the Catalog filter in the left column
2. Select the checkbox next to **Software**
The results now contain only those which belong to the Software category. These are actually all going to be Catalog Item results.
You should see something that looks like below
(screenshot 5)
3. Click the **Clear (1)** link next to the Categories filter to remove it
### Exercise 6 - Explore synonyms
1. Enter `laptop` in the search box and hit the ENTER key
Notice how the word `laptop` is highlighted? You likely even see some results where `Mac` and/or `PC` is highlighted. 
This is because `Mac` and `PC` are configured as synonyms of `laptop` in the default out-of-the-box (OOTB) synonymn dictionary.
(screenshot 6)
Synonyms are bi-directional, so searching for `PC` will also match and highlight `Mac` and `laptop`. Try it!
### Exercise 7 - Explore typo handling
1. Enter `ipone` in the search box and hit the ENTER key
Notice how the the search term was auto-corrected to `iphone`? There is also a link offered that allows the user to bypass the spelling correction and instead search for the term exactly how it was entered. 
(screenshot 7)
### Exercise 8 - Explore stop words
1. Enter `The windows key` in the search box and hit the ENTER key
Notice how the word `the` is not hilighted? The word `the` is such a common word in English, and so many documents in the index will contain it, that searching for it doesn't help the user find what they are looking for. It is what we call a *stop word* which means it is ignored by the search engine.
Try other queries which contain other stop words such as `I`, `a`, `if` and `for`.
(screenshot 8)
### Exercise 9 - Explore Genius Results
1. Enter `paassword reset` in the search box and hit the ENTER key
You should see something that looks like below
(screenshot 9)
The larger, featured result at the top of the results is what is called a *Genius Result*. The OOTB Genius Results include catalog items, people and Question and Answers (Q&A).
### Exercise 10 - Impersonate a user
1. Impersonate the user **Abraham Lincoln**
2. Re-open the Service Portal
3. Enter `***` in the search box and hit the ENTER key
4. Click on the **Knowledge** tab
Notice there are no Knowledge results? The Abraham Lincoln user does not have the necessary permissions to access any Knowledge articles OOTB. By impersonating this user, Abraham Lincoln's permissions are enforced by AI Search.
(screenshot 10)
