# Set up vcpkg

This GitHub action uses
[friendlyanon/setup-vcpkg](https://github.com/friendlyanon/setup-vcpkg) to properly set up
vcpkg and cache it. Some inputs were cut down for simplification, but others were added to
enable using [Fantana's private vcpkg
registry](https://github.com/fantana21/vcpkg-registry). See [action.yml](action.yml) for
details.
