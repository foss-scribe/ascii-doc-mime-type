# AsciiDoc mime type package for Ubuntu

I use Pluma to write documentation in AsciiDoc format but found that Pluma would not display *.adoc files in it's side panel without a proper mime type package/declaration.

Once these files are deployed to ~/.local/share/mime, AsciiDoc files with an adoc extension are recognised as a valid text file by the system.

## Installation

1. Copy/Symlink x-adoc.xml to ~/.local/share/mime/text
2. Copy/Symlink text-x-adoc.xml to ~/.local/share/mime/packages


For a detailed description see: https://ubuntu-mate.community/t/creating-new-mime-types/4351
