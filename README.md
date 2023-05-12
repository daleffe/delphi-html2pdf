# Delphi/Lazarus Template

 Delphi/Lazarus template project

## Delphi

### RTTI

If you don't use RTTI, put follow lines at start of your project file (.dpr):

```delphi
{$WEAKLINKRTTI ON}
{$RTTI EXPLICIT METHODS([]) PROPERTIES([]) FIELDS([])}
```

It'll save ~500 kb of your generated *.exe*.
