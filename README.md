readme coming....

next...
√ build out make_urls()
    √ print the type of the initial random number.
    √ move the random number maker to a lib.rs function.
    √ move the results-dict-initializer to a lib.rs function.
    √ start trying to update the results-dict.
    √ convert the four-character numeral to a float.
    √ add the float to the httpbin url-day.
    √ store the httpbin url to the results-dict as a json-string.
    √ revise hashmap to hold another hashmap.
    √ redo update urls now that we have a hashmap of hashmaps.
        √ I've build the new url, next to figure out how to update the hashmap.
√ move make_urls() to lib.rs.
- write up this readme.
- create the file that will be written to synchronously.
- set up dummy architecture to create a queue of jobs, limited by a capacitor/semaphore number.
- have each job do some work (initially a simply delay of seconds, but later a call to httpbin) -- and then write the results to the backup file synchronously.


Note: for this template, I'll really store everything to a dict with the job-name being the four-character repreentation of the httpbin delay, and storing the amazon-id -- with the write being a "backup".