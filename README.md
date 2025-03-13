# delphi_fastreport_farsi_xlml_all_ver
for design and preview forms in persian(farsi) language   all versions  above 6.4 -to-2024


procedure fr_locale(masir: string = '');
begin

  if masir = '' then
    masir := c:\farsi\';

  frxResources.LoadFromFile(masir +'frxrcClass.xml');
  frxResources.LoadFromFile(masir +'frxrcDesgn.xml');
  frxResources.LoadFromFile(masir + 'frxrcExports.xml');
  frxResources.LoadFromFile(masir + 'frxrcInsp.xml');
end;
