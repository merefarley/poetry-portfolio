import random
pronouns = ["I", "he", "she", "it"]
action = ["was walking to", "was running to", "was skipping to", "was dashing to", "was sprinting to"]
article = ["the"]
place = ["hot dog stand", "ocean", "beach house", "bay", "dock", "tackle shop", "yacht club", "ice cream shop"]
thing = ["beach patrons","lifeguard","dolphin","shark", "starfish", "stingray", "fish", "umbrella", "sun", "waves", "ball"]

print ("After waking up", random.choice (pronouns))
print (random.choice(action))
print (random.choice(article))
print (random.choice(place))
print ("to search for")
print (random.choice(article))
print (random.choice (thing)) 
print ("which will ensure the best beach day ever") 
