# whiteboard
Just another canvas whiteboard app

------
TOOLS: 
  P - paintbrush
  R - rectangle
  E - ellipse
  L - line
  M - measure

------
OTHER CONTROLS
  backtick, 0 - 9: select brushes, hold to set colors.
    the color palettes are arranged as follows:
      Left - paintbrush color
      Center - overlay color
      Right - grid color

  V - place vanishing point
  G - select between no grid, a square grid, and a triangular grid
  J - select manner in which grid cells are outlined
  I - reset unsplash image
  S - bring paintbrush marks to foreground, allowing you to right-click and "save image as"

Ctrl:
  constrains paintbrush to grid axes, or commits to straight line, if no grid is visible
  constrains rectangle and ellipse to 1x1 aspect ratio
  line to 15° increments

Arrow Keys: 
  Up constrains paintbrush to vertical
  Left constrains paintbrush to horizontal
  Down constrains to lines to and away from the vanishing point
  Right constrains to arcs about the vanishing point
  Forward Slash constrainst to lines parallel to the most recent line made with the paintbrush in committed constraint
  
------
QUERY PARAMETERS
  document-title
  screen-size
  board-size
  wallpaper-image
  overlay-color
  grid-type (two numbers, between 0 and 2, separated by 'x')
  problem-active
  problem-image
  marks-image
  fill-active
  
  
