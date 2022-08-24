# Test Case Samples

## For damarc.ro website:

#### Title
Test contact form

#### Description
Test whether the contact form functions with all fields filled in correctly.

#### Steps to reproduce
1. Go to https://www.damarc.ro/contact/
2. Fill in all fields in the form
3. Press "Trimite" button

#### Expected result
Email should be received on company email account with correct info (from the form).

#### Test data
- Name: Test_123
- Sender Email: place.holder@gmail.com
- Subject: Test_123
- Message: Test_123

**This test has been automated due to its low complexity, high frequency and high time demand**
**You can check the code in the *Test Automation* repository**



## For emag.ro website:

#### Title
Test Search bar results

#### Description
Test whether the search term introduced in the search bar returns that particular item/items.


#### Steps to reproduce
1. Go to emag.ro
2. Input "iPhone x" in the search bar
3. Click Search / press enter key
4. Observe search results


#### Expected result
The results should be iPhone X smartphones with different hardware configurations.
______________________________________________________________________________________________



#### Title
Test search bar autocomplete

#### Description
Test whether the search bar autocompletes a particular word before having typed it completely.


#### Steps to reproduce
1. Go to emag.ro
2. Input "iPho" in the search bar
3. Observe what word is autocompleted



#### Expected result
The search bar should autocomplete the term and suggest "iPhone".
______________________________________________________________________________________________

#### Title
Test search bar with incorrect search term

#### Description
Test search bar by using incorrect/nonsense search term.


#### Steps to reproduce
1. Go to emag.ro
2. Input "tqunv iohpUGITQFIOUNG" in the search bar
3. Click Search / press enter key
4. Observe behaviour


#### Expected result
The page should display >0 rezultate pentru: "tqunv iohpUGITQFIOUNG"


