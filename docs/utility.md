# Utility

## 8ball

Get a randomized answer to your question.

=== "Usage"

    ```
    !8ball <question>
    ```

=== "Example"

    Input:

    ```
    !8ball Is this a cool documentation?
    ```
    Output:
    ```
    Absolutely!
    ```

## coin

Flip a coin.

=== "Usage"

    ```
    !coin
    ```

=== "Example"

    Input:

    ```
    !coin
    ```
    Output:
    ```
    {username}, you flipped heads!
    ```

## endpoll

!!! info "This command can only be used by mods"
End an ongoing poll and display the result.

=== "Usage"

    ```
    !endpoll
    ```

=== "Example"

    Input:

    ```
     !endpoll
    ```
    Output:
    ```
    Poll results for: Is Squirtle the best Pokémon?
    Yes: 10 votes
    No: 0 votes
    ```

## endpredict

!!! info "This command can only be used by mods"
End an ongoing poll and display the result.
If no value is written the prediction defaults to "false".

=== "Usage"

    ```
    !endpredict <true | false>
    ```

=== "Example"

    Input:

    ```
     !endpoll
    ```
    Output:
    ```
    Prediction Results for: Can I beat the next level?
    Outcome: True
    Gussed correctly (3): {user1}, {user2}, {user3}
    Guessed incorrectly (1): {user4}
    ```

## guess

Take a guess on the currently ongoing prediction.

=== "Usage"

    ```
    !guess <true | false>
    ```

=== "Example"

    Input:

    ```
     !guess true
    ```
    Output:
    ```
    {user} your guess of "true" has been recorded!
    ```

## lookup

Look up a term on various sites.
=== "Usage"

    ```
    !lookup <wikipedia | urban> <term>
    ```

=== "Example"

    Input:

    ```
     !lookup wikipedia cat
    ```
    Output:
    ```
    The cat (Felis catus), also referred to as the domestic cat, is a small domesticated carnivorous mammal.
    ```

## poll

!!! info "This command can only be used by mods"
Start a poll with multiple options.

=== "Usage"

    ```
    !poll <question> | <answer1> | <answer2> | <answer n>
    ```

=== "Example"

    Input:

    ```
    !poll Is this a question? | Yes | No | Maybe | I don't know | Can you repeat the question?
    ```
    Output:
    ```
     📊 New poll: Is this a question?
     Option 1: Yes
     Option 2: No
     Option 3: Maybe
     Option 4: I don't know
     Option 5: Can you repeat the question?
     Vote by typing !vote [option number]
    ```

## predict

!!! info "This command can only be used by mods"
Start a prediction with only true or false options.

=== "Usage"

    ```
    !predict <question>
    ```

=== "Example"

    Input:

    ```
    !predict Will I beat the next level?
    ```
    Output:
    ```
     🔮 Prediction: Will I beat the next level?
     "Make your guess by typing !guess true or !guess false."
    ```

## remindme

Set a reminder for minutes or hours.

=== "Usage"

    ```
    !remindme <number><m | h> <message>
    ```

=== "Example"

    Input:

    ```
    !remindme 10m Don't forget to hydrate!
    ```
    Output:
    ```
     {user},  I'll remind you in 10m.

     {user}, here's your reminder: Don't forget to hydrate!
    ```

## roll

Roll one or multiple dice.

=== "Usage"

    Amount can be ommitted for 1.

    ```
    !roll <amount><type>
    ```

=== "Example"

    Input:

    ```
    !roll 2d20
    ```
    Output:
    ```
     {user} rolled 2d20: [19, 10] - Total: 29
    ```

## translate

Translate a sentence.

=== "Usage"

    Punctuaton is important.

    ```
    !translate <origin language> <target language> <text>
    ```

=== "Example"

    Input:

    ```
    !translate en de This is a sentence.
    ```
    Output:
    ```
     {user}, translation: Das ist ein Satz.
    ```

## vote

Cast a vote on the currently ongoing poll.

=== "Usage"

    ```
    !vote <number>
    ```

=== "Example"

    Input:

    ```
    !vote 1
    ```
    Output:
    ```
     {user}, your vote for "Yes" has been recorded!
    ```
