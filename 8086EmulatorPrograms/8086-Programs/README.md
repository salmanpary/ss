# 8086 Programs for Evaluation

## [Arithmetic](https://github.com/jacobjohn2016/8086-Programs/tree/master/Arithmetic)
1. Addition of 2 8b numbers [add_8b_2.asm](Arithmetic/add_8b_2.asm)
2. Subtraction [sub_8b.asm](Arithmetic/sub_8b.asm)
3. Multiplication [multiply_8b.asm](/Arithmetic/multiply_8b.asm)
4. Division of 16b with 8b number [divide_16b_by_8b.asm](/Arithmetic/divide_16b_by_8b.asm)
5. Addition of 2 16b [add_8b_16b.asm](Arithmetic/add_8b_16b.asm)
6. Multiplication of 2 32b [multiply_2_32b.asm](/Arithmetic/multiply_2_32b.asm)
7. Sum of n 8b [Sum_of_n_8b.asm](/Arithmetic/Sum_of_n_8b.asm)
8. Print array [print_array.asm](Arithmetic/print_array.asm)
9. Add two 8bit numbers [add_8b_2.asm](/Arithmetic/add_8b_2.asm)
10. Load Effective Address [lea.asm](/Arithmetic/lea.asm)
11. Offset [offset.asm](/Arithmetic/offset.asm)
12. Count number of 1s in a binary number [count_1s.asm](/Arithmetic/count_1s.asm)
13. Find the largest number among 5 grades [find_largest.asm](/Arithmetic/find_largest.asm)
14. Divide 16b by 8b [divide_16b_by_8b.asm](/Arithmetic/divide_16b_by_8b.asm)
15. Add 16b with carry [add_16b_carry.asm](/Arithmetic/add_16b_carry.asm)
16. Add 16b BCD [add_16b_bcd.asm](/Arithmetic/add_16b_bcd.asm)
17. Decimal Adjust after addition [daa.asm](/Arithmetic/daa.asm)

## [Expression](https://github.com/jacobjohn2016/8086-Programs/tree/master/Expression)
18. ALP to find the Greatest Common Divisor of two unsigned integer.[gcd_two.asm](/Expression/gcd_two.asm)
19. ALP to find the Sum and average of unsigned integer. [sum_average_unsigned.asm](/Expression/sum_average_unsigned.asm)
20. Develop and execute an ALP to compute factorial of a positive integer number using recursive procedure. [fact.asm](/Expression/fact.asm)
21. Transfer string from one memory location to another. [copy_string_memory_location.asm](/Expression/copy_string_memory_location.asm)
22. Count vowels in a word [count_vowels.asm](/Expression/count_vowels.asm)
23. Calculate power(a,b) i.e a^b [power.asm](/Expression/power.asm)
24. Average of values stored in an array. [average_sum_array.asm](/Expression/average_sum_array.asm)
25. Find Reverse of an array. [reverse_array.asm](/Expression/reverse_array.asm)
26. Prompts the user to enter an array and displays it [prompt_user_array+display.asm](/Expression/prompt_user_array%2Bdisplay.asm)
27. Find largest number in memory location [finding_largest_number_memory.asm](/Expression/finding_largest_number_memory.asm)
28. Check if number is even or odd [check_number_even_odd.asm](/Expression/check_number_even_odd.asm)
29. Check if given number is prime [given_number_prime.asm](/Expression/given_number_prime.asm)
30. Fibonacci Sequence [fibonacci.asm](/Expression/fibonacci.asm) || [fibonacci2.asm](/Expression/fibonacci2.asm) || [fibonacci3.asm](/Expression/fibonacci3.asm)
31. Concatenation of strings [concatenation_string.asm](/Expression/concatenation_string.asm)
32. Check if string contains substring [substring_in_string.asm](/Expression/substring_in_string.asm)
33. Count number of words [count_words.asm](/Expression/count_words.asm)

## [Conversion](https://github.com/jacobjohn2016/8086-Programs/tree/master/Conversion)
34. ALP for conversion of 16-bit HEX number into its equivalent BCD number.[hex_bcd.asm](/Conversion/hex_bcd.asm)
35. ALP for conversion of 16-bit BCD number into its equivalent HEX number. [bcd_hex.asm](/Conversion/bcd_hex.asm)
36. ALP for conversion BCD number 7-Segment String. [seven_segment.asm](/Conversion/seven_segment.asm)
37. ALP to copy the string of successive memory locations from one memory to other.

    a. Using string instructions [copy_string_instruction.asm](/Conversion/copy_string_instruction.asm)
    
    b. Without using string instruction [copy_without_string_instruction.asm](/Conversion/copy_without_string_instruction.asm)
38. Compare two strings [compare_strings.asm](/Conversion/compare_strings.asm)
39. Reverse a number [reverse_number.asm](/Conversion/reverse_number.asm)
40. Decimal to binary [decimal_to_binary.asm](/Conversion/decimal_to_binary.asm)
41. Decimal to octal [decimal_to_octal.asm](/Conversion/decimal_to_octal.asm)
42. Hexadecimal to decimal [hex_to_decimal.asm](/Conversion/hex_to_decimal.asm)

## [Sorting](https://github.com/jacobjohn2016/8086-Programs/tree/master/Sorting)
43. ALP to Sort a set of unsigned integer numbers in ascending/ descending order using Bubble sort algorithm. [bubble_sort.asm](/Sorting/bubble_sort.asm)
44. Array Ascending [array_ascending.asm](/Sorting/array_ascending.asm)
45. Array Descending [array_descending.asm](/Sorting/array_descending.asm)

## [Searching](https://github.com/jacobjohn2016/8086-Programs/tree/master/Searching)
46. Develop and execute ALP that implements Binary search algorithm. The data consists of sorted 16 bit unsigned integers. The search key is also a 16 bit unsigned integer. [binary_search.asm](/Searching/binary_search.asm)
47. Search Element in an array [search_element_array.asm](/Searching/search_element_array.asm)
48. Linear Search [linear_search.asm](/Searching/linear_search.asm)
49. Occurences of character [occurences_character_count.asm](/Searching/occurences_character_count.asm)

# Assessment Programs

1. Emulate a counter on emu8086, to count the no. of 1???s (binary) in the given input value. [count_1s.asm](/Arithmetic/count_1s.asm)
2. Emulate water level controller on emu8086 for the following Specifications: [water_level_controller.asm](/Simulation/water_level_controller.asm)
    * No. of water levels in the overhead tank is 8
    * Display the current level of water with a buzzer
    * Switch on the motor if the water level is 1
    * Switch off the motor if the water level is 8
    * Switch on the buzzer on water overflow
3. Emulate a fire monitoring system on emu8086 for the following specifications: [fire_monitoring_system.asm](/Simulation/fire_monitoring_system.asm)
    * Define the threshold for the temperature of two rooms
    * Generate the temperature value in 8b resolution
    * Switch on the alarm and display an alarm message when the threshold of either of the room is reached
    * Remove the alarm and bring the temperature below the threshold
4. Design and Emulate a smart automation system for a garment manufacturing unit with the following requirements:- [garment_defect.asm](/Simulation/garment_defect.asm)
    * To detect all possible defects.
    * To remove the defective pieces.
    * To provide comprehensive inventory report.
5. Find the largest number from an unordered array of sixteen 8-bit numbers stored sequentially in memory location 2000:5000H. Store the largest number in memory location 2000:5000H.[finding_largest_number_memory.asm](/Expression/finding_largest_number_memory.asm)

# [External add-on devices](https://github.com/jacobjohn2016/8086-Programs/tree/master/External%20Devices)

*__Note:__ All the given programs must be emulated using emu8086 only.*
[Download link](http://www.emu8086.com)

1. Traffic Lights
    * [traffic_lights](/External%20Devices/traffic_lights.asm)
    * [traffic_lights2](/External%20Devices/traffic_lights2.asm)
2. LED display [LED_display_test.asm](/External%20Devices/LED_display_test.asm)
3. Stepper Motor [stepper_motor.asm](/External%20Devices/stepper_motor.asm)
4. Thermometer [thermometer.asm](/External%20Devices/thermometer.asm)
5. Robot [robot.asm](/External%20Devices/robot.asm)
6. Timer [timer.asm](/External%20Devices/timer.asm)
7. Keyboard [keybrd.asm](/External%20Devices/keybrd.asm)
8. Mouse [mouse.asm](/External%20Devices/mouse.asm)
