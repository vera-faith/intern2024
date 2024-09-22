# LLM Deliverable Week 6

## Team:

### LLM intern team 1 - Prisha S. and Faith D. 

---

## Backwards Chaining System for FOL

* FOL (First-Order-Logic) is a system used to represent relations between expressions.  

## Tutorial:

* I decided to implement this from scratch using my family members.
* In my code, I started off with creating a knowledge base, that contains facts of my Father, Mother, and Grandmother and who their children are.
* Then, I created a simple backward-chaining system to check if a query matches the prompted fact.
* I tested one false query and one true query and the results were accurate. 
---

## GitHub

knowledge_base = [
    ('Father', 'Oliver','Faith'),
    ('Mother', 'Anna', 'Faith'),
    ('Mother', 'Leticia', 'Oliver')
]

def backward_chain(query):
    for fact in knowledge_base:
        if fact == query:
            return True
        return False

query = ('Father', 'Faith', 'Anna')
result = backward_chain(query)
print(f"Query {query}: {result}")

query = ('Father', 'Oliver', 'Faith')
result = backward_chain(query)
print(f"Query {query}: {result}")
