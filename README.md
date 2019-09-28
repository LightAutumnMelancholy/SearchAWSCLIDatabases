# SearchAWSCLIDatabases
 Go find databases in my aws profile across all configured regions matching string. ###
		   
    [EXAMPLE]: scriptname -d prod-client-ignite-db -p my-amazon-profile -o table -m 2 -l 25"
          
    [REQUIREMENTS]: This script requires only two arguments -d and -p, and requires the user to have setup aws profiles setup in order to use this tool.
		  
    [REQUIRED ARGUMENTS]:
      -d) [database] [STRING] This option refers to the database name to search for. The search will match any correctly spelled approxmation.
      -p) [profile] [STRING] This option refers to the profile to be used for AWS. This should exist in $HOME/.aws/credentials.
		  
    [OPTIONAL ARGUMENTS]:
      -o) [Output Type] [STRING]This option sets the output type. Defaults to JSON, accepts text | table | json.
      -m) [Matches] [INTEGER] This option sets the amount of matches to return.
      -l) [Output Lines] [INTEGER] This option sets the amount of output lines per match to return.
      -h) [HELP] [takes no arguements] Print this dialog to the screen.
