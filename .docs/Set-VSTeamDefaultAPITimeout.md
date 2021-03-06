<!-- #include "./common/header.md" -->

# Set-VSTeamDefaultAPITimeout

## SYNOPSIS

<!-- #include "./synopsis/Set-VSTeamDefaultAPITimeout.md" -->

## SYNTAX

## DESCRIPTION

By setting a default timeout you can adjust the value for your needs

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------

```PowerShell
PS C:\> Set-VSTeamDefaultAPITimeout 30
```

This command sets 30 seconds as the default timeout.

## PARAMETERS

<!-- #include "./params/force.md" -->

### -TimeoutSec

Specifies the timeout for all function calls.

```yaml
Type: Int
Required: True
Accept pipeline input: False
```

### -Level

On Windows allows you to store your default timeout at the Process, User or Machine levels.

When saved at the User or Machine level your default timeout will be in any future PowerShell processes.

```yaml
Type: String
```

## INPUTS

### System.String

## OUTPUTS

### System.Object

## NOTES

## RELATED LINKS
