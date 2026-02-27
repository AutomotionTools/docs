# Loop Examples

Rive below

<canvas id="voting" width="200" height="80" role="spinbutton" aria-valuenow="994" aria-valuetext="994 likes"></canvas>
<script>

</script>

Rive above

## Cycle

=== "Loop In"

    ![Loopy panel with Cycle button highlighted](../assets/loopy/example_loops/Continue%20-%20In%20Out.gif)

    ```jsx
    loopIn("continue");
    ```

=== "Loop Out"

    ![Loopy panel with Cycle button highlighted](../assets/loopy/example_loops/Continue%20-%20In%20Out.gif)

    ```jsx
    loopOut("continue");
    ```

=== "Loop In + Out"

    ![Loopy panel with Cycle button highlighted](../assets/loopy/example_loops/Continue%20-%20In%20Out.gif)

    ```jsx
    loopIn("continue") + loopOut("continue") - value;
    ```

## Cycle (with Keyframe Modifier)

=== "Loop In (with Keyframe Modifier)"

    ![Loopy panel with Cycle button highlighted](../assets/loopy/example_loops/Cycle%20-%20In%20-%20Keyframe.gif  )

    ```jsx
    loopIn("cycle", 2);
    ```

=== "Loop Out (with Keyframe Modifier)"

    ![Loopy panel with Cycle button highlighted](../assets/loopy/example_loops/Continue%20-%20In%20Out.gif)

    ```jsx
    loopOut("cycle", 2);
    ```

=== "Loop In + Out (with Keyframe Modifier)"

    ![Loopy panel with Cycle button highlighted](../assets/loopy/example_loops/Continue%20-%20In%20Out.gif)

    ```jsx
    loopIn("cycle", 2) + loopOut("cycle", 2) - value;
    ```

## Continue

=== "Loop In"

    ![Loopy panel with Cycle button highlighted](../assets/loopy/example_loops/Continue%20-%20In.gif)

    ```jsx
    loopIn("continue");
    ```

=== "Loop Out"

    ![Loopy panel with Cycle button highlighted](../assets/loopy/example_loops/Continue%20-%20Out.gif)

    ```jsx
    loopOut("continue");
    ```

=== "Loop In + Out"

    ![Loopy panel with Cycle button highlighted](../assets/loopy/example_loops/Continue%20-%20In%20Out.gif)

    ```jsx
    loopIn("continue") + loopOut("continue") - value;
    ```

!!! note "Note"

    The '*Continue*' loop type does not support keyframe modifiers.