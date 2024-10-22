To start your mongo shell type the following command :

mongosh

To create Codetribe database use the following command :

use Codetribe.

To create a collection create the following command :

db.createCollection('Facilitators')

db.createCollection('Trainee')

db.createCollection('Projects')

For Facilitators collection insert a document that contains the following Command:

db.facilitators.insertOne({name: "Kabelo", Location: "Kimberley", Course: "Backend"})

For Trainees collection insert a document that contains the following Command:

test> db.Trainee.insertOne({name: "Lesego", Location: "Kimberley", facilitator: "Kabelo"})

For Projects collection insert a document that contains the following Command:

db.Project.insertOne({name: "Creating database", Course: "Mongodb", Lesson: 5})

