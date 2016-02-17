Users
{

}

Game State
{
  _id: ObjectId("asdkfjsdklfjsdfjeie"),
  p1: {
    deck: {},
    hand: {},
    discard: {}
  },
  p2: {
    deck: {},
    hand: {},
    discard: {}
  },
  shop: {},
  turn: {
    player: "P1",
    step: "" // Action, Buy
  }
}

Action P1 -> played -> ajax -> save action to db -> success -> continue
Action P1 -> played -> ajax -> save action to db -> success -> continue
Press Pass -> ajax -> save pass to db -> success -> continue
Buy P1 -> buy - ajax -> save buy to db -> succes -> continue
Press Pass -> ajax -> save pass to db -> success -> continue
client -> cleanup -> manage decks -> action

Save/Load

Deck
[
  { // base
    initial: {},
    empty: {}
  },
  { // intrigue
    initial: {},
    empty: {}
  }
]
