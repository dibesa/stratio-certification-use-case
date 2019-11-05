# Sparta Workflow
Sparta workflow for labelling data using the model and the external data. The workflow has two differentiated parts: the first part where data is adapted as the data input accepted by the model and a second part where the labelling is done as follows:
* **Red:** If risk probability is greater than 60% or the requester has been involved in three or more fraud cases.
* **Green:** Not Red and risk probability is under 15% or the requester has not been involved in any fraud case.
* **Yellow** The remaining cases.