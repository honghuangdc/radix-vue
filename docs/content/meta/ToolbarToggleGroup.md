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
    'name': 'defaultValue',
    'description': '<p>The default active value of the item(s).</p>\n<p>Use when you do not need to control the state of the item(s).</p>\n',
    'type': 'string | string[]',
    'required': false
  },
  {
    'name': 'dir',
    'description': '<p>The reading direction of the combobox when applicable. &lt;br&gt; If omitted, inherits globally from <code>ConfigProvider</code> or assumes LTR (left-to-right) reading mode.</p>\n',
    'type': '\'ltr\' | \'rtl\'',
    'required': false
  },
  {
    'name': 'disabled',
    'description': '<p>When <code>true</code>, prevents the user from interacting with the toggle group and all its items.</p>\n',
    'type': 'boolean',
    'required': false
  },
  {
    'name': 'loop',
    'description': '<p>When <code>loop</code> and <code>rovingFocus</code> is <code>true</code>, keyboard navigation will loop from last item to first, and vice versa.</p>\n',
    'type': 'boolean',
    'required': false
  },
  {
    'name': 'modelValue',
    'description': '<p>The controlled value of the active item(s).</p>\n<p>Use this when you need to control the state of the items. Can be binded with <code>v-model</code></p>\n',
    'type': 'string | string[]',
    'required': false
  },
  {
    'name': 'orientation',
    'description': '<p>The orientation of the component, which determines how focus moves: <code>horizontal</code> for left/right arrows and <code>vertical</code> for up/down arrows.</p>\n',
    'type': '\'vertical\' | \'horizontal\'',
    'required': false
  },
  {
    'name': 'rovingFocus',
    'description': '<p>When <code>false</code>, navigating through the items using arrow keys will be disabled.</p>\n',
    'type': 'boolean',
    'required': false
  },
  {
    'name': 'type',
    'description': '<p>Determines whether a &quot;single&quot; or &quot;multiple&quot; items can be pressed at a time.</p>\n<p>This prop will be ignored if any of <code>v-model</code> or <code>defaultValue</code> is defined, as the type will be inferred from the value.</p>\n',
    'type': '\'single\' | \'multiple\'',
    'required': false
  }
]" />

<EmitsTable :data="[
  {
    'name': 'update:modelValue',
    'description': '<p>Event handler called when the value changes.</p>\n',
    'type': '[payload: string | string[]]'
  }
]" />
