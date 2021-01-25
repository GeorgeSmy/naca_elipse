/*--------------------------------*- C++ -*----------------------------------*\
| =========                 |                                                 |
| \\      /  F ield         | OpenFOAM: The Open Source CFD Toolbox           |
|  \\    /   O peration     | Version:  v1712                                 |
|   \\  /    A nd           | Web:      www.OpenFOAM.com                      |
|    \\/     M anipulation  |                                                 |
\*---------------------------------------------------------------------------*/
FoamFile
{
    version     2.0;
    format      ascii;
    class       volScalarField;
    location    "0";
    object      nut;
}
// * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * //

dimensions      [ 0 2 -1 0 0 0 0 ];

internalField   uniform 0.0002678;

boundaryField
{
    walls
    {
        type            zeroGradient;
    }
	
    naca0012
    {
        type            nutLowReWallFunction;
        value           uniform 0;
    }
    elipse
    {
        type            nutLowReWallFunction;
        value           uniform 0;
    }
    inlet
    {
        type            fixedValue;
        value           uniform 0.0002678;
    }
    outlet
    {
        type            zeroGradient;
    }
    front
    {
        type            empty;
    }
	back
    {
        type            empty;
    }
}


// ************************************************************************* //
