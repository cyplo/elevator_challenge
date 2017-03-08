# Elevator kata
* as a user of the elevator I want to get from the floor I am at to my desired floor
* protobuf binary socket-based interface
* 'people waiting at floor F' async event
* you can put your move in the queue, i.e. post 'as an elevator I want to go to floor Fd next'

# Elevator challenge
* whole day workshop
* do the kata first
* provide test framework - simulator of a building
* framework is provided at the start, anyone can run a simulation
* after some time the global simulator and scoring starts
* each team deploys an elevator
* the whole time the whole building works, there are people on each floor that want to get to another floor
* the elevator can take in at most P persons between floors
* run time of the algorithm counts, as your elevator busy time
* the elevator that took the most people where they wanted to go wins
* there is a piece of data that represents a person you need to pull from one floor and then return to destination floor
* penalty for returning people to the wrong floor
* if you take more than T time to get form the floor to another floor the maintenance team comes and takes your elevator out of order for Z time
* if your program crashes while people were inside your elevator - you killed them - your elevator is taken out for investigation by the government for I time

