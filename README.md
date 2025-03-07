# Parametric Cokin P style filter holder

This is a parametric FreeCAD model for a Cokin P style filter holder.
It can support filter threads of various sizes and pitches up to about a 67mm diameter.

## Hardware description

The threaded part has a friction ring; on this friction ring the actual holder is mounted on with a tight fit.

M3 machine screws are needed to fix the spacers and spring plates to the filter holder.
Choose the length based on the number of plates you need to sandwich together (e.g. for a 3 filter configuration 5 plates are needed - spacer, spring, spacer, spring, spacer - and M3x14 screws are a good fit).

## Printing

The `threaded-cap` needs to be printed with a 0.1mm layer height.
The rest of the parts can use a 0.2mm (or more) layer height.

## Assembly

After printing `threaded-cap` and `filter-holder`, assemble them together so that the cap's lip sits within the relief in the holder and the surfaces are flush.
Initially there is a very slight interference fit between the two parts; rotate one of them within the other to have the surfaces wear out and rotate smoother.

Stack the separator/spacer plates and spring plates together for the desired number of filters:
* for a single filter: separator, spacer, separator
* for two filters: separator, spacer, separator, spacer, separator
* etc

Use M3 machine screws to fasten the stacks to the filter holder body **on the side where the surface is flush**.
Choose screw lengths that are appropriate for the stack sizes.

## Changing parameters

The FreeCAD file has a spreadsheet named *Dimensions*. Edit this spreadsheet, specifically the `ThreadNominalDiameter` and `ThreadPitch` parameters.

## License

This project is licensed under the Creative Commons BY-SA 4.0 license. See LICENSE for more details.
