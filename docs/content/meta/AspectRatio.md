<!-- This file was automatic generated. Do not edit it manually -->

<PropsTable :data="[
  {
    'name': 'as',
    'description': '<p>The element or component this component should render as. Can be overwritten by <code>asChild</code>.</p>\n',
    'type': 'AsTag | Component',
    'required': false,
    'default': '\'div\''
  },
  {
    'name': 'asChild',
    'description': '<p>Change the default rendered element for the one passed as a child, merging their props and behavior.</p>\n<p>Read our <a href=\'https://www.radix-vue.com/guides/composition.html\'>Composition</a> guide for more details.</p>\n',
    'type': 'boolean',
    'required': false
  },
  {
    'name': 'ratio',
    'description': '<p>The desired ratio. Eg: 16/9</p>\n',
    'type': 'number',
    'required': false,
    'default': '1'
  }
]" />

<SlotsTable :data="[
  {
    'name': 'aspect',
    'description': '<p>Current aspect ratio (in %)</p>\n',
    'type': 'number'
  }
]" />
