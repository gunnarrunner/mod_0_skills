Instance: RedWingBoot

Attributes
- type_of_material: "leather"
- is_damaged: false
- number_of_shoe_strings: 4
- parts_of_shoes: ["tongue", "sole", "strings"]


Methods
- change_shoe (changes type_of_material to polyester)
- rip_shoe (updates is_damaged to true)
- lose_string (updates number_of_shoe_strings to 3)
- damage_part (deletes tongue from parts_of_shoes array)
