num_1 = 4
num_2 = 3
def my_shiny_new_decorator(function_to_decorate):
     def the_wrapper_around_the_original_function():
         summa = num_1 + num_2
         function_to_decorate()
         num_3 = summa*2

     return the_wrapper_around_the_original_function
