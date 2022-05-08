# CS361-helpBot

This is a helpBot microservice!
You can install it in your Python CLI.

## Requirements:
    * create a "helpMe.txt" file

## To launch service use:

    def write_help():
    with open("helpMe.txt", "w") as f:
        f.write("help")

## To retrieve message from file:

    def get_help():

        with open("helpMe.txt") as f:
            helpful_message = f.readline()

        return helpful_message
