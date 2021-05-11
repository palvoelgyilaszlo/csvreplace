# csvReplace

    require_once '../vendor/autoload.php';

    use Palvoelgyi\CsvRepace\CsvRepace;
# Use for information:

    $CsvRepace = new CsvRepace;

    $CsvRepace
        ->setDir('../csvdata') // for example "../csvdata"
        ->isDir()
        ->getInfo();
# Use for replace:

    $CsvRepace = new CsvRepace;

    $CsvRepace
        ->setDir('../csvdata') // for example "../csvdata"
        ->isDir()
        ->replaceData();