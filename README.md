people = []

print("People Counter")

while True:
    name = input("Enter a person's name or type 'done': ")

    if name.lower() == "done":
        break

    people.append(name)
    print(f"Current number of people: {len(people)}")

print(f"\nTotal people: {len(people)}")
print("People:", ", ".join(people))
