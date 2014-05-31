# pmedit

Simple wrapper command to edit Perl Module files.

## Usage

```
$ pmedit [OPTIONS] <Module Path>
```

```<Module Path>``` is location in perl.
For example, "File::Path" is the ```<Module Path>``` when you want to edit it.
(Though I think it's rare case you want to edit it.)

So you should include your perl's @INC if you want to edit your modules by this command.

Or you will be able to edit them like this:

```
$ pmedit -l<path> Your::Module
```

