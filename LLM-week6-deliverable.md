# LLM Deliverable Week 6

## Team:

### LLM intern team 1 - Prisha S. and Faith D. 

---

## Deontic Logic Presantation:

* Backwards Chaining system for FOL 

## Implementation and Tests run:

This inforgraphic is a one-page tutorial on how to use Deontic Logic.

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
