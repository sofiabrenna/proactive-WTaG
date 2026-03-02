# Proactivity-Annotated WTaG Dataset
The files consists in 11 dialogues from the Watch-Talk-and-Guide dataset (https://github.com/sled-group/Watch-Talk-and-Guide) that have been manually annotated for the presence of _proactivity_ in multimodal task-guidance dialogues in the recipes domain.

- WTaG_annotato_textual.json contains annotations made with access exclusively to dialogue transcriptions of the WTaG interactions;
- WTaG_annotato_multimodal.json contains annotations made with full multimodal access: namely, textual and audio-visual context of the WtaG interactions.

Proactivity is defined by both novelty/initiative and helpfulness, and each proactive utterance is classified into one of the following dialogue acts:

• NONE — participant A does not produce an utterance that is simultaneously unsolicited and helpful: the utterance is not proactive.

• NOTIFICATION — participant A gives some information to addressee B, A makes B aware of some information.

• SUGGESTION — A suggests an action or an option that they believe to be potentially promising for achieving a certain goal.

• OFFER — A offers to do something in order to help B or to achieve the dialogue goal.

• INFO-REQUEST — A is asking for some information or instruction from B.

• ACTION-REQUEST — A wants B to perform the requested action, conditional on B’s consent.

• INSTRUCTION — A wants B to perform an action and/or is instructing B on how to do it.

• INTERVENTION — A directly performs an action in the environment to help achieve the dialogue goal.

## WTaG Distribution
Access to the Watch-Talk-and-Guide dataset is managed by its owners according to its license (https://github.com/sled-group/Watch-Talk-and-Guide).

## Contributors
- Sofia Brenna (Free University of Bozen-Bolzano, Fondazione Bruno Kessler)
- Matthias Kraus (University of Augsburg)
- Elisabetta Jezek (Univerity of Pavia)
- Bernardo Magnini (Fondazione Bruno Kessler)
