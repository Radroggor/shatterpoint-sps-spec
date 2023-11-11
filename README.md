# Shatterpoint Strike Team Format Specification

This specification facilitates the export and subsequent import of Strike Team for AMG's Star Wars: Shatterpoint game from one compliant application to another.

Thanks to Eli Stevens and the contributors for their work on X-Wing Squadron Specification version 2.0.0, which inspired me for this project.

## Goals
* Allow users to easily move a Strike Team from one Team Building app to another
* Allow users to share a Strike Team without dictating how it should be viewed
* Back up Strike Team without being tied to a specific app to restore them
* Be future-proof
* Be human-readable


## Strike Team Data Format (Shatterpoint Strike Team Format or .SPS)
A container can be represented as a stand-alone JSON file encoded in UTF-8 with either an .sps or a .json extension. MIME types of application/json or text/plain SHOULD be accepted by API endpoints.

A Strike Team is generally a single player's list used for a Star Wars: Shatterpoint match.

Note that no assertion of tournament-legality is made for a Strike Team represented in this format. While the specification targets tournament legal lists, there are some rules of list construction that are not enforced by this specification (point totals, duplicated units, etc.).

Importing implementations MUST perform validation before making assumptions about the appropriate nature of a list for any given purpose.


# TO DO #
