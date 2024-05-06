# Battlefield in Ruby

Welcome to the Battlefield project in Ruby! This project aims to create a text-based battlefield game using the Ruby programming language. Each contributor will work on their own branches to add features, fix bugs, and improve the game.

## Getting Started

To get started with this project, follow these steps:

ADD STUFF HERE 

## Google Docs

### Notes: 
https://docs.google.com/document/d/1Afb3DhTnHuYEm99SuH-ms4uWVM2rCyWp5mLNOpQZz5c/edit

### Summary Report
https://docs.google.com/document/d/1NRdUbh7hrRafQ7HD_Pj2098iv1Ia3Xo6oA2SxyYyp7A/edit?pli=1

class BattleshipGame

  ### constructor
  def initialize
  @board = 
  @ships = {}
  end

  ###places ships randomly on board, horizontal/vertical
  def placeShips
  end

  ###Checks if a ship can be placed at the specified position on the board without overlapping    ###or going out of bounds
  def canPlaceShip?(x, y, size, direction)
  end
  
  ###Takes coordinates from parameter and check if the shot hits a ship, misses or is already     ###shot. Then updates board
  def shoot(x,y)
  end

  ###Updates the board when a ship is hit. If complete, mark as sunk
  def shipHit(x,y)
  end

  ###Checks if all ships are sunk
  def gameOver
  end

  ###Displays the current state of the board
  def displayBoard
  end

  
