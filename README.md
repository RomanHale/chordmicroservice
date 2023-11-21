A. To programmatically REQUEST data from the microservice I implemented, create a text file named 
    "client_key.txt" that contains the user's desired key followed by an underscore followed by the word 
    yes or the word no.
        An example text file could contain one the following:
            "c_no" or "eb_yes"
        
B. To programmatically RECEIVE data from the micorservice I implemented, open a text file using the
    name "server_key.txt" and read the data as in the following example code.
        An example of opening and grabbing the data from the file would look like this:
            infile = open('server_key.txt', 'r')
            chords_in_user_key = infile.read()
            infile.close()

C.![diagram](https://github.com/RomanHale/chordmicroservice/assets/59492487/4ad57086-72ed-4cbf-b107-b2a9332325c5)

