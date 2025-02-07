# Horse-raceOOP

this is the diagram
also sorry if this is not what you wanted i have been sick and have been trying to learn only from the videos i will be back in class on monday so again sorry i should have told you earlier 

Horse
_____________________
- id: int        
- position: int
______________________
- Horse(int)
- advance(): void
- getPosition(): int
- getId(): int

contains

Race
- horses: vector<Horse>
- trackLength: int
___________________________
- Race(int, int)
- start(): void
- advanceHorses(): void
- displayRace(): void
- isFinished(): bool

also here is the agarithem

id: Unique identifier for each horse.

position: Current position of the horse on the track.

Methods:

Horse(int id): Constructor initializes the horse's ID and position to 0.

advance(): Moves the horse forward by one step with a 50% probability.

getPosition() const: Returns the current position of the horse.

getId() const: Returns the ID of the horse.

Race

horses: A list of Horse objects participating in the race.

trackLength: Defines the length of the race track.

Methods:

Race(int numHorses, int trackLength): Constructor initializes the race with a given number of horses and track length.

start(): Controls the main race loop, displaying progress and checking for race completion.

advanceHorses(): Calls advance() on each horse to update their positions.

displayRace() const: Displays the current race state in a simple text-based format.

isFinished() const: Checks if any horse has reached or passed the finish line.


if there is anything wrong with this repo please let me know what to change
