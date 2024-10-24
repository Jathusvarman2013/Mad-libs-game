def mad_libs():
    print("Welcome to Mad Libs!")
    # Get user input for different parts of speech
    adjective = input("Enter an adjective: ")
    noun = input("Enter a noun: ")
    verb = input("Enter a verb: ")
    adverb = input("Enter an adverb: ")
    place = input("Enter a place: ")
   
    # Create the story
    story = f"Once upon a time in a {adjective} {place}, there was a {noun} that loved to {verb} {adverb}."
   
    print("\nHere's your story:")
    print(story)

# Start the game
mad_libs()
