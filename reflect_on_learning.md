Major topics
1) Recursive algorithms
2) Nested data structures
3) Debugging
4) Ennumerable methods
5) Iterative algorithms
6) Code design
7) How to write methods that perform the same function as block methods without writing block methods
8) How to write iterative algorithms without using block methods
9) How to write recursive algorithms without a recursive call
10) How to write methods that perform the same function as ennumerable methods without using the ennumerable methods

Ennumerable methods
I learned that with ennumerable methods it's possible to perform some very specific functions with just one line of code. So much happens in that one line and it blows my mind.

Example:

    vowel_search = word_array.find { |vowel| vowels.include?(vowel) }
    consonants = word_array.take_while { |consonants| consonants != vowel_search }

Recursive algorithms
I learned that recursive algorithms are actually rather simple. In order to write one I just need to define its restrictions in the base case.

Example:

  def recursive_nth_fibonacci_number(n)
    if n == 0
      0
    else
      1
    end
    recursive_nth_fibonacci_number(n-1)+recursive_nth_fibonacci_number(n-2)
  end
