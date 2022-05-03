{
  'name': 'Babelgum'
}

{}

{
  'number_of_employees': {
    '$ne': 5000
  }
}

{}

{
  '$and': [
    {
      'founded_year': {
        '$gt': 1999
      }
    }, {
      'founded_year': {
        '$lt': 2006
      }
    }
  ]
}

{}

{
  '$and': [
    {
      'acquisition.price_amount': {
        '$gte': 100000000
      }
    }, {
      'founded_year': {
        '$lte': 2010
      }
    }
  ]
}

{}

{
  '$and': [
    {
      'number_of_employees': {
        '$gte': 100
      }
    }, {
      'founded_year': {
        '$lte': 2005
      }
    }
  ]
}

{}

{
  'category_code': {
    '$type': 'null'
  }
}
{}

{
  '$and': [
    {
      'founded_year': {
        '$lt': 2000
      }
    }, {
      'acquisition.price_amount': {
        '$gte': 10000000
      }
    }
  ]
}

{}

{
  'acquisition.acquired_year': {
    '$gte': 2010
  }
}

{}

{
  'founded_year': {
    '$exists': true
  }
}
{}

{
  'founded_day': {
    '$lte': 7
  }
}
{}

{
  '$and': [
    {
      'category_code': 'web'
    }, {
      'number_of_employees': {
        '$gte': 4000
      }
    }
  ]
}

{}

{
  '$and': [
    {
      'acquisition.price_amount': {
        '$gte': 100000
      }
    }, {
      'acquisition.price_currency_code': 'EUR'
    }
  ]
}
{}

{
  'acquisition.acquired_month': {
    '$lte': 3
  }
}

{}

{
  '$and': [
    {
      'founded_year': {
        '$gte': 2000
      }
    }, {
      'founded_year': {
        '$lte': 2010
      }
    }, {
      'acquisition.acquired_year': {
        '$lte': 2011
      }
    }
  ]
}




