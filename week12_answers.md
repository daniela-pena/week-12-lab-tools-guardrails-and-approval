# Week 12 answers

## Exercise 1
1. The messages the customer typed: "I want to change my shipping address", "It's order A102", and "9 Pine Street. Tampa".
2. How many tool requests were refused, and why: 2, because the first used order A100 and the second used the incorrect address, neither of which were used/typed by the customer.
3. If the customer now types "thanks", how many messages does Ollama receive on the next call? 14 messages.
4. Why does "Do you sell gift cards?" still go to a person, and why is that acceptable? Because one of the rules (payment rule) detects 'card' in the message, and a missed question regarding payment could expose confidential card information to the model.

## Exercise 3

1. Output:
(.venv) danielapena@Mac module10_agents_backup % python3 main.py
Type a message, or type quit to stop.
You: I want to change my shipping address
Sunny: Your request to change the shipping address has been submitted to staff for approval. Please wait for their confirmation.
You: quit
Messages in this conversation: 3
Staff review
Request 1: A100 to 123 Main St, Anytown, AN 12345
Approve? yes or no: no
Request 1 rejected.
A100 14 Bay Road
A101 3 Gull Lane
A102 88 Pier Street