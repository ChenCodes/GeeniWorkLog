# GeeniWorkLog
keeping track of what work I've done for Geeni

####Start: Friday July 8th
      Work completion:
      Work done: 6 hours (10am - 4pm)
      File: Viewcontroller.swift 
      Lines of code: ~80
      What did I do: Implemented the following things:
                  Story: User Login first time Conditions:
                  User already has an account
                  User has never logged into this device before
                  User logs in correctly with username and password
                  Result:
                  —> Sees newsfeed
                  
                   Story: User Loggin before with this device Conditions:
                  User already has an account
                  User has logged into this device before
                  User launches app.
                  Result:
                  —> Sees newsfeed (doesn't see login field)
                  
                   Story: User Loggin with username doesn't exist Conditions:
                  User has an account
                  User types in a username that doesnt exist
                  User presses loggin
                  Result:
                  —> Sees alertview still on loggin screen
                  
                   Story: User Loggin with username and wrong password Conditions:
                  User doesn't have an account
                  User types in a correct username but wrong password
                  User presses loggin
                  Result:
                  —> Sees alertview still on loggin screen
    File: registrationOne.swift
    Lines of code: ~300
    What did I do?:
              Implemented a firstname/lastname checker.
              Implemented a major checker.
              Implemented a password field checker(needs to be 8 characters long, have at least one numeric character, and a special character as well as a capital character. 
               Story : User cannot use any profanity in their first name last name (TROLL BLOCKER)
                        User is registering
                        User types in a profane word
                        Result
                        --> Return a false value
                        (Alex: text field will turn red)
                        
                         Story: User does not have a long enough password
                        User is registering
                        User uses a password that is not safe enough (8 characters long, capital letters the whole shebang whatever)
                        Result
                        --> Return a false value
                        (Alex: text field will turn red)
                        (continue button will not be installed)
                        
                         Story: User has already registered with this email
                        User is registering
                        User uses an already existing email address
                        Result
                        --> Return a UIAlertView
                        (continue button will not be installed)
                        
                         Story: User is not using a berkeley.edu email
                        User is registering
                        User uses something that doesnt end in .edu
                        Result
                        --> Return a UIAlertView
                        (continue button will not be installed)
                        
                         Story: User checks if two password fields
                        User is registering
                        User types in valid password
                        User types in correct second password
                        Result
                        --> Return a false value
                        (continue button will not be installed)
                        (fields will be red)
        File: verificationController.swift
        Lines of code: ~40
                Implementation: Made 4 textfields so that the user can enter in their code and delete correctly. They enter in a code from their email. 
                
                
####Monday July 11th
      File: newsFeedNewConroller.swift
      Lines of code: ~100 
      
      @ChenCodes
             Story : Populate the TableView with a custom TableViewCell
             User can see all necessary information
      @ChenCodes
            Story : Table View Functionality
            User sees Newsfeed page
            User clicks on a cell
            User is brought to a details page (describes interaction in more detail ie what they worked on, what the person may need to improve on, idk, not even sure if this exists)
      
      @ChenCodes
      Story: Time stamp function
      
####Tuesday July 12th

