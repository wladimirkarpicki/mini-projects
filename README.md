Outer loop
│
├── Create secret number
├── Reset attempts
│
└── Guessing loop
    │
    ├── Validation loop
    │   ├── "hello" → error → ask again
    │   └── "50" → continue
    │
    ├── Increase attempts
    ├── Compare guess
    │
    └── Correct → break
│
├── Ask play again?
│
└── "n" → break
