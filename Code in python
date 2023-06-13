Python 3.11.0 (main, Oct 24 2022, 18:26:48) [MSC v.1933 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license()" for more information.
>>> 
... # Taking string as input, to be converted.
... x = str(input("Type your sentence/character you want to convert in Morse Code."))
... 
... # Changing string to uppercase
... upper_x = x.upper()
... print(f"Your input is: {x}")
... 
... # Dictionary containing morse code
... morse_code ={ 'A':'._', 'B':'_...',
...                     'C':'_._.', 'D':'_..', 'E':'.',
...                     'F':'.._.', 'G':'__.', 'H':'....',
...                     'I':'..', 'J':'.___', 'K':'_._',
...                     'L':'._..', 'M':'__', 'N':'_.',
...                     'O':'___', 'P':'.__.', 'Q':'__._',
...                     'R':'._.', 'S':'...', 'T':'_',
...                     'U':'.._', 'V':'..._', 'W':'.__',
...                     'X':'_.._', 'Y':'_.__', 'Z':'__..',
...                     '1':'.____', '2':'..___', '3':'...__',
...                     '4':'...._', '5':'.....', '6':'_....',
...                     '7':'__...', '8':'___..', '9':'____.',
...                     '0':'_____', ', ':'__..__', '.':'._._._',
...                     '?':'..__..', '/':'_.._.', '-':'_...._',
...                     '(':'_.__.', ')':'_.__._'}
... 
... # Spliting the sentence into a list of words
... word_list = list(upper_x.split(" "))
... 
... # Creating a loop to get access to the words of word_list
... for j in word_list:
...     # Creating a list to get characters of words
...     list_j = [*j]
... 
...     #Another loop to access the characters of the words
...     for i in list_j:
...         # Checking if character matches any key value of dictionary.
...         if i in morse_code:
            print(f"{morse_code[i]}",end=" ")
    # This print statement will simply add / after every word_list sub list.
    print(end="/")


