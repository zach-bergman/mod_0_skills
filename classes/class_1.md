# Class: FastFood

- Attributes:
  - name (string)
  - dollar_menu (array)
  - hours_open (string)
  - drive_thru_spaces (integer)
  - dining_room_clean (boolean)


- Methods:
  - change_open_hours (modifies the hours_open attribute)
  - new_dollar_menu (modifies the elements inside the dollar_menu array)
  - is_drive_thru_full(num) (checks the num parameter with the current value of the drive_thru_spaces attribute, returns boolean value)
  - clean_dining_room (checks the value of the dining_room_clean attribute, if false, this method changes the value to true)
