# RefractiveIndex
is a MATLAB function to return the complex wavelength-dependent refractive index of ice, water, soot, or dust.
The data for water come from Hale & Querry, Applied Optics 1973, https://doi.org/10.1364/AO.12.000555.
The data for ice come from several sources. By default the function returns the values from Warren & Brandt, JGR 2008, https://doi.org/10.1029/2007JD009744,
with values inserted from Picard et al., The Cryosphere 2016, https://doi.org/10.5194/tc-10-2655-2016.
Options available include the Warren & Brandt data without the Picard et al. insertion, or the values from Warren Applied Optics 1984, https://doi.org/10.1364/AO.23.001206.
Values for dust are from McKenzie Skiles measurements (J Glaciology 2017, https://doi.org/10.1017/jog.2016.126) and Charlie Zender's website (http://dust.ess.uci.edu/smn/smn_cgd_200610.pdf).
Soot values from from Bond & Bergstrom, Aerosol Science and Technology 2006, https://doi.org/10.1080/02786820500421521.

Future changes would include more dust members from various regions and information about brown carbon from Nic Beres and Hans Moosmüller.
